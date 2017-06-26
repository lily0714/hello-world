<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
<script type="text/javascript"> 
$(document).ready(function() { 
$("p.interest").css({cursor:"pointer"}).click(function(){
  $(".in1").slideToggle("slow");
  $(".in2").slideToggle("slow");
  $(".in3").slideToggle("slow");
});
$("p.in1").css({cursor:"pointer"}).click(function(){
  $(".draw").fadeIn("fast");
  $(".diy").fadeOut("fast");
  $(".post0").fadeOut("fast");
  $(".music").fadeOut("fast");
});
$("p.in2").css({cursor:"pointer"}).click(function(){
  $(".diy").fadeIn("fast");
  $(".draw").fadeOut("fast");
  $(".post0").fadeOut("fast");
  $(".music").fadeOut("fast");
});
$("p.in3").css({cursor:"pointer"}).click(function(){
  $(".music").fadeIn("fast");
  $(".draw").fadeOut("fast");
  $(".post0").fadeOut("fast");
  $(".diy").fadeOut("fast");
});
$(".categoryho").click(function(){
   $(".category").toggle("fast");
   $(".categoryho").toggle({left:"200px"});
});
});
</script>
<style> 
.infortitle{ 
background-color:#DDAA00; 
width:160px; 
height:20px; 
color:#FFFFFF; 
font-size: 14px; 
} 
.ipic{
display:block;
margin:auto;
}
.post{ 
background-color:#DDAA00;
width:100px; height:30px; 
color:#FFFFFF; 
font-size:16px; 
position:relative;
left:1px;
}
.draw{
display: none;
}
.diy{
display: none;
}
.music{
display: none;
}
.dcontent{
color:#BB5500;
font-size:12px;
text-align:left; 
}
.post1{
width:50%;
height:auto;
position:relative;
left:0px;
}
p { 
font-size: 12px; 
font-family: Monospace; 
color:#BB5500; 
text-align:center;
} 
.categoryho{
width:30px;
height:170px;
background-color:#dc7d1f;
color:white;
float:left;
position:relative;
top:200px;
z-index:5;
}
.categoryho:hover{
left:5px;
color:yellow;
outline:none;
border-color: #dc7d1f;
box-shadow:0 0 10px #dc7d1f;
cursor:pointer;
}
.category{
width:200px;
height:100%;
float:left;
display:none;
background-color:#dc7d1f;
color:white;
position:fixed;
z-index:5;
}
body{ 
double #FFF; 
background-color:#FFEE99; 
word-wrap:break-word; 
margin:0; 
}
ul {
list-style-type: none;
}
#bantitle{
background-color:#FFFFE0;
border-style:dotted;
border-color:#DDAA00;

}
#banner{ 
background-repeat:no-repeat;
background-position:center;
margin:5px 5px; 
padding:0;
position:relative;
left:140px;
} 
#title{  
text-align:center; 
font-family: Lobster, Monospace;
color:#8F5924; 
} 
#subtitle{ 
color:#B8732E; 
}
#WRAPPER { 
/*margin:0 auto;*/
width:980px; 
/*padding:0 10px;*/ 
/*overflow:auto;*/ 
background-color:#FFFFE0;
border-style:dotted;
border-color:#DDAA00;
} 
#CONTENT {
margin-left:200px; 
width:902px;
height:550px;
float:none;
} 
#LSIDE { 
float:left;
width:162px; 
border-width:2px; 
border-left-style:solid; 
border-right-style:solid; 
border-bottom-style:solid; 
border-color:#DDAA00; 
}  
#RSIDE { 
float:right;
width:162px;  
heigt:520px;
border-left-style:dotted;  
border-bottom-style:dotted; 
border-color:#DDAA00; 
}  
.icontent{
text-align:left;
}
#FOOTER { 
margin:0 auto; 
width:1024px; 
height:120px; 
}
.interest{
background:#FFCC22;
}
.interest:hover{ 
/*滑鼠移至區塊變色*/
background: #DDAA00;
text-decoration:underline;
color:#FFFFFF;
}
.in1{ 
display: none;
width: 100%;
padding: 10px 0px;
background: #FFEE99;
}
.in1:hover{ 
/*滑鼠移至區塊變色*/
background: #DDAA00;
text-decoration:underline;
color:#FFFFFF;
}
.in2{ 
display: none;
width: 100%;
padding: 10px 0px;
background: #FFEE99;
}
.in2:hover{ 
/*滑鼠移至區塊變色*/
background: #DDAA00;
text-decoration:underline;
color:#FFFFFF;
}
.in3{ 
display: none;
width: 100%;
padding: 10px 0px;
background: #FFEE99;
}
.in3:hover{ 
/*滑鼠移至區塊變色*/
background: #DDAA00;
text-decoration:underline;
color:#FFFFFF;
}
/*超連結*/ 
a:link { 
color: saddlebrown; 
} 
a:visited { 
color: saddlebrown; 
} 
a:hover { 
color: #FF8C00; 
} 
a:active { 
color: orange;
} 
</style>
   <body>
   <div class="categoryho">
   點我查看更多</div>
   <div class="category">
      <ul>個人興趣
      <li>畫畫</li>
      <li>手做</li>
      <li>演奏樂器</li>
      </ul>
      </div>
  
   <div id="bantitle">
   <img id="banner" src="http://lily0714.github.io/20170424改.jpg" width="700" height="400">
  
   </div>
   <div id="WRAPPER">
      <div id="LSIDE">
          <div id="infor">
          <p class="infortitle">個人資料</p>
          <img class="ipic" src="http://lily0714.github.io/IMG_20161102_213309.jpg" width="145" height="249">
          <ul>
          <p class="icontent">是個喜歡音樂、自我矛盾很嚴重的孩子。</p>
          <p class="icontent">姓名:陸映螢</p>
          <p class="icontent">學校:輔仁大學</p>
          <p class="icontent">學系:資訊工程學系</p>
          <p class="icontent">生日:0 7 月 1 4 日</p>
          <a class="url icontent" href="https://github.com/lily0714"><b>我的GitHub</b></a> 
          </ul>
          </div>
      </div>
      <div id="RSIDE">
         <div class="menu">
           <p class="interest">個人興趣</p>
           <p class="in1">畫畫</p>
           <p class="in2">手做</p>
           <p class="in3">演奏樂器</p>
         </div>
      </div>
      <div id="CONTENT">
         <div class="post0">
           <p>這是lily0714的網頁</p>
           <p>點選右邊以查看更多內容</p>
         </div>
         <div class="draw">
            <br>
            <p class="post">畫畫</p>
            <img class="post1" src="http://lily0714.github.io/畫畫1.png" >
            <a href="http://lily0714.github.io/畫畫1.png"><br>點我看大圖</a>
            <div class="dcontent">
            　<br>
               這大概是從國中就開始畫的，我都叫他小饅頭人。<br>
               一開始只是隨手畫畫，並沒有想太多，但後來他成了我一小部分的自己。<br>
               也許是長越大越覺得世界太複雜，他的存在總能時時提醒我小時候的單純。<br>
               而且我喜歡把他畫在甜點世界或是遊樂場，就像小孩一樣容易因為一些小事而開心的不得了。
            </div>
         </div>
         <div class="diy">
            <p class="post">手做</p>
            <img class="post1" src="http://lily0714.github.io/手做一.png" >
            <a href="http://lily0714.github.io/手做一.png"><br>點我看大圖<br></a>
            <div class="dcontent">
               這是最近幾天做的桌曆。<br>
               原本是只買了計畫紙，突如其來的靈感讓我想把它變成桌曆。<br>
               這成本其實大概三十塊錢，而且封面是可以"撕下"每年做替換的。<br>
               其實上面的那兩隻小熊也是我縫的，印象中他們也陪我兩三年有了吧。<br>
               其他手做等以後再慢慢更新吧。
            </div>
         </div>
          <div class="music">
            <p class="post">演奏樂器</p>
            <img class="post1" src="http://lily0714.github.io/music.png" >
            <a href="http://lily0714.github.io/music.png"><br>點我看大圖<br></a>
            <div class="dcontent">
               高中的時候，曾經想學吉他。<br>
               但因為手太小按不好和弦，當時家裡又有烏克麗麗的玩具，於是就開始學習烏克的和弦及刷法。<br>
               靠著影片自學，漸漸學會了堪稱是"烏克麗麗界國歌"的小手拉大手。<br>
               之後，除了靠影片自學，大一也加入社團學習。<br>
               上了大學總想做點什麼特別的事，於是就又接觸了一個樂器－－口琴。<br>
               加入口琴社從一開始的複音口琴，再來和弦口琴，最後半音階口琴，其中我感受到的一個要點是，<br>
               ＂不管學什麼樂器，節奏都是很重要的。＂<br>
               漸漸地，聽歌不再是只聽旋律部份，還會聽背景的鼓聲、低音部份，<br>
               藉由這種練習，我發現對演奏樂器或是唱歌都很有用，都能穩穩地跟著節奏完成一首歌。
            </div>
         </div>
       </div>
   </div>
   <div id="FOOTER"> 
      <img src="http://lily0714.github.io/底.png" width="1024" height="60">
   </div>
   </body>

