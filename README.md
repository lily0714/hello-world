<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
<script type="text/javascript"> 
$(document).ready(function() { 
$("#btodreamstory").css({cursor:"pointer"}).mouseenter(function(){
  $("#todreamstory").show();
  $("#btodreamstory").hide();
});
$("#todreamstory").css({cursor:"pointer"}).mouseleave(function(){
  $("#btodreamstory").show();
  $("#todreamstory").hide();
});
$("p.interest").css({cursor:"pointer"}).click(function(){
  $(".in1").slideToggle("slow");
  $(".in2").slideToggle("slow");
  $(".in3").slideToggle("slow");
});
$("p.dream").css({cursor:"pointer"}).click(function(){
  $(".dream1").fadeIn("fast");
  $(".diy").fadeOut("fast");
  $(".post0").fadeOut("fast");
  $(".music").fadeOut("fast");
  $(".draw").fadeOut("fast");
  $(".leave").fadeOut("fast");
});
$("p.in1").css({cursor:"pointer"}).click(function(){
  $(".draw").fadeIn("fast");
  $(".diy").fadeOut("fast");
  $(".post0").fadeOut("fast");
  $(".music").fadeOut("fast");
  $(".dream1").fadeOut("fast");
  $(".leave").fadeOut("fast");
});
$("p.in2").css({cursor:"pointer"}).click(function(){
  $(".diy").fadeIn("fast");
  $(".draw").fadeOut("fast");
  $(".post0").fadeOut("fast");
  $(".music").fadeOut("fast");
  $(".dream1").fadeOut("fast");
  $(".leave").fadeOut("fast");
});
$("p.in3").css({cursor:"pointer"}).click(function(){
  $(".music").fadeIn("fast");
  $(".draw").fadeOut("fast");
  $(".post0").fadeOut("fast");
  $(".diy").fadeOut("fast");
  $(".dream1").fadeOut("fast");
  $(".leave").fadeOut("fast");
});
$("p.homepage").css({cursor:"pointer"}).click(function(){
  $(".post0").fadeIn("fast");
  $(".draw").fadeOut("fast");
  $(".music").fadeOut("fast");
  $(".diy").fadeOut("fast");
  $(".dream1").fadeOut("fast");
  $(".leave").fadeOut("fast");
});
$("p.message").css({cursor:"pointer"}).click(function(){
  $(".leave").fadeIn("fast");
  $(".post0").fadeOut("fast");
  $(".draw").fadeOut("fast");
  $(".music").fadeOut("fast");
  $(".diy").fadeOut("fast");
  $(".dream1").fadeOut("fast");
});
$(".categoryho").click(function(){
   $(".category").css({left:"-20px"});
   $(".categoryho").hide();
   $(".categoryhide").show();
});
$(".categoryhide").click(function(){
   $(".category").css({left:"-200px"});
   $(".categoryhide").hide();
   $(".categoryho").show();
});
$("h1").hide();
});
var ymdw = new Date();
var y = ymdw.getFullYear() , m = ymdw.getMonth()+1 , d = ymdw.getDate() , w = ymdw.getDay();
var weekday=["星期日","星期一","星期二","星期三","星期四","星期五","星期六"];
msg1=weekday[w];
</script>
<style> 
.infortitle{ 
background-color:#DDAA00; 
width:160px; 
height:20px; 
color:#FFFFFF; 
font-size: 14px; 
font-family: Microsoft JhengHei;
} 
.ipic{
display:block;
margin:auto;
}
.icon{
background-color:#ffffe0;
}
.post{ 
background-color:#DDAA00;
width:100px; height:30px; 
color:#FFFFFF; 
font-size:16px; 
position:relative;
left:1px;
font-family: Microsoft JhengHei;
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
.dream1{
display:none;
}
.leave{
display:none;
}
.postdate {
position: relative;
right: -350px;
top: -50px;
font-size:13px;
color:#bb5500;
}
.dcontent{
color:#BB5500;
font-size:12px;
text-align:left; 
font-family: Microsoft JhengHei;
}
.post1{
width:50%;
height:auto;
position:relative;
left:25px;
font-family: Microsoft JhengHei;
}
p { 
font-size: 12px; 
font-family: Microsoft JhengHei; 
color:#BB5500; 
text-align:center;
} 
.categoryho{
width:30px;
height:170px;
background-color:#dc7d1f;
color:white;
float:left;
position:fixed;
top:200px;
left:0px;
z-index:5;
border-radius:0px 10px 10px 0px;
text-align:center;
font-family: Microsoft JhengHei;
}
.categoryhide{
width:30px;
height:170px;
background-color:#c36f1b;
color:white;
float:left;
position:fixed;
top:200px;
left:180px;
z-index:6;
display:none;
border-radius:0px 10px 10px 0px;
text-align:center;
font-family: Microsoft JhengHei;
}
.categoryho:hover{
color:yellow;
outline:none;
border-color: #dc7d1f;
box-shadow:0 0 10px #dc7d1f;
cursor:pointer;
left:3px;
}
.categoryhide:hover{
color:yellow;
outline:none;
border-color: #dc7d1f;
box-shadow:0 0 10px #dc7d1f;
cursor:pointer;
}
.category{
width:200px;
height:450px;
float:left;
background-color:#de944b;
color:white;
position:fixed;
z-index:5;
left:-200px;
border-radius:0px 20px 20px 0px;
font-family: Microsoft JhengHei;
}
.category:hover{
border-color: #dc7d1f;
box-shadow:0 0 10px #dc7d1f;
}
#cat_home{
background-color:#ffee99;
color:white;
font-size:16px;
position:relative;
top:20px;
}
.cat_item{
background-color:#bb5f43;
color:white;
font-size:16px;
position:relative;
top:20px;
}
.cat_inin:hover{
background-color:white;
opacity:0.95;
color:#dc7d1f;
}
body{ 
double #FFF; 
background-color:#FFEE99; 
word-wrap:break-word; 
margin:0;
font-family:Microsoft JhengHei;
}
ul {
list-style-type: none;
font-family: Microsoft JhengHei;
}
#bantitle{
background-color:#FFFFE0;
border-style:dotted;
border-color:#DDAA00;
font-family: Microsoft JhengHei;
width:980px;
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
height:586px;
/*padding:0 10px;*/ 
/*overflow:auto;*/ 
background-color:#FFFFE0;
border-style:dotted;
border-color:#DDAA00;
font-family: Microsoft JhengHei;
} 
#CONTENT {
margin-left:200px; 
width:902px;
height:550px;
float:none;
font-family: Microsoft JhengHei;
} 
#LSIDE { 
float:left;
width:162px;
position:relative;
left:4px;
top:4px;
border-width:2px; 
border-left-style:solid; 
border-right-style:solid; 
border-bottom-style:solid; 
border-color:#DDAA00; 
font-family: Microsoft JhengHei;
}  
#RSIDE { 
float:right;
width:162px;  
heigt:520px;
border-left-style:dotted;  
border-bottom-style:dotted; 
border-color:#DDAA00; 
font-family: Microsoft JhengHei;
}  
.icontent{
text-align:left;
font-family: Microsoft JhengHei;
}
#FOOTER { 
margin:0 auto; 
width:980px; 
height:60px; 
}
.r-cat{
background:#FFCC22;
font-family: Microsoft JhengHei;
}
.r-cat:hover{ 
/*滑鼠移至區塊變色*/
background: #DDAA00;
text-decoration:underline;
color:#FFFFFF;
}
#todreamstory {
display:none;
position:relative;
left:2px;
top:2px;
}
.in1{ 
display: none;
width: 100%;
padding: 10px 0px;
background: #FFEE99;
font-family: Microsoft JhengHei;
}
.in1:hover{ 
/*滑鼠移至區塊變色*/
background: #DDAA00;
text-decoration:underline;
color:#FFFFFF;
}
#todraw {
position: relative;
left: 50px;
top: 10px;
}
#todraw:hover {
top: 15px;
left:52px;
cursor: pointer;
}
.in2{ 
display: none;
width: 100%;
padding: 10px 0px;
background: #FFEE99;
font-family: Microsoft JhengHei;
}
.in2:hover{ 
/*滑鼠移至區塊變色*/
background: #DDAA00;
text-decoration:underline;
color:#FFFFFF;
}
#todiy {
position: relative;
left: 50px;
top: 10px;
}
#todiy:hover {
top: 15px;
left:52px;
cursor: pointer;
}
.in3{ 
display: none;
width: 100%;
padding: 10px 0px;
background: #FFEE99;
font-family: Microsoft JhengHei;
}
.in3:hover{ 
/*滑鼠移至區塊變色*/
background: #DDAA00;
text-decoration:underline;
color:#FFFFFF;
}
.leavecon{
font-size:14px;
}
#alllea {
    font-size: 14px;
    position: relative;
    left: 30px;
    top: 30px;
    width: 500px;
    
}
#yourname{
position: relative;
left: 10px;
}
#checklea {
    color: white;
    background-color: #cc6d1e;
    width: 60px;
}
#get-day{
width:180px;
height:40px;
padding-left: 8px;
font-size:14px;
color:white;
float:right;
position:relative;
bottom:10px;
background-color:#DDAA00;
font-family:Microsoft YaHei;
}
/*category超連結*/ 
a:link { 
color:#990000; 
} 
a:visited { 
color:#990000; 
} 
a:hover {  
color:#990000;
} 
a:active { 
color: orange;
} 
</style>
   <body>
<div class="categoryho">點我查看更多</div>
   <div class="categoryhide">點我收起來</div>
   <div class="category">
   <p id="cat_home"><a href="https://lily0714.github.io/">首 頁</a></p>
   <ul><p class="cat_item">夢想萌芽</p>
------------------------
   <li class="cat_inin"><a href="https://lily0714.github.io/dreamstory">灌溉過程</a></li>
   </ul>
   <ul><p class="cat_item">個人興趣</p>
   ------------------------
   <li class="cat_inin"><a href="https://lily0714.github.io/interest/draw">畫畫</a></li>
   <li class="cat_inin"><a href="https://lily0714.github.io/interest/diy">手做</a></li>
   <li class="cat_inin"><a href="https://lily0714.github.io/interest/music">演奏樂器</a></li>
   </ul>
   <ul><p class="cat_item">留言板</p>
   -----------------------
   </ul>
   </div>
   <div id="bantitle">
   <img id="banner" src="http://lily0714.github.io/image/20170424改.jpg" width="700" height="400">
  
   </div>
   <div id="WRAPPER">
      <div id="LSIDE">
          <div id="infor">
          <p class="infortitle">個人資料</p>
          <img class="ipic" src="http://lily0714.github.io/20170628.jpg" width="150" height="210">
          <ul><br>
          <p class="icontent">是個喜歡音樂、自我矛盾很嚴重的孩子。</p>
          <p class="icontent">姓名:陸映螢</p>
          <p class="icontent">學校:輔仁大學</p>
          <p class="icontent">學系:資訊工程學系</p>
          <p class="icontent">生日:0 7 月 1 4 日</p>
          </ul>
          </div>
      </div>
      <div id="RSIDE">
         <div class="menu">
           <p class="r-cat homepage">主 頁</p>
           <p class="r-cat dream">夢想萌芽</p>
           <p class="r-cat interest">個人興趣</p>
           <p class="in1">畫畫</p>
           <p class="in2">手做</p>
           <p class="in3">演奏樂器</p>
           <p class="r-cat message">留言板</p>
         </div>
      </div>
      <div id="CONTENT">
         <div class="post0">
         <center>
         <p>----------------------------</p>
           <p>這是lily0714的網頁</p>
           <p>開站日期:2017/03/18</p>
         <p>----------------------------</p>
         <p>右邊選單為單個項目的一篇文章</p>
         <p>若想看全部文章，請點左邊列表的項目，</p>
         <p>將會帶您到該項目的所有文章頁面:D</p>
           </center>
         </div>
         <div class="dream1">
         <br>
         <p class="post">種子出現</p>
            <a href="https://lily0714.github.io/seed1.jpg" target="_blank"><img class="post1" src="https://lily0714.github.io/seed1.jpg" ></a>
            <div class="dcontent">
               故事是從國小六年級開始的。<br>
               當初是因為電腦課要經營Xuite的blog，相信許多人都有學過這堂課。<br>
               有天老師上課上到一半說，隔壁班的某位同學部落格做得很漂亮，並切畫面展示給大家看。<br>
               看到的當下我有個想法，明明和我們是同年級，她怎麼可以做的那麼漂亮又精緻?<br>
               於是之後，我就找了很多資料，發現要學的東西實在很多。<br>
               除了製圖技巧，還要會排版呢!感覺真的很困難...所以就拿了別人提供的版型語法嘗試做修改。<br>
               雖然看的不是很懂，但看哪裡變了，就是改到哪個東西。<br>
               於是就做出了第一個版型:D
               <div>
               <a href="https://lily0714.github.io/dreamstory"><img id="btodreamstory" src="https://lily0714.github.io/心路歷程1.png"><img id="todreamstory" src="https://lily0714.github.io/todreamstory1.gif"></a>
               </div>
            </div>
         </div>
         <div class="draw">
            <br>
            <p class="post">畫畫</p>
            <a href="http://lily0714.github.io/畫畫1.png" target="_blank"><img class="post1" src="http://lily0714.github.io/畫畫1.png" ></a>
            <div class="dcontent">
            　<br>
               這大概是從國中就開始畫的，我都叫他小饅頭人。<br>
               &nbsp; &nbsp; 一開始只是隨手畫畫，並沒有想太多，但後來他成了我一小部分的自己。<br>
               &nbsp; &nbsp; 也許是長越大越覺得世界太複雜，他的存在總能時時提醒我小時候的單純。<br>
               &nbsp; &nbsp; 而且我喜歡把他畫在甜點世界或是遊樂場，就像小孩一樣容易因為一些小事而開心的不得了。
               <div>
               <a href="https://lily0714.github.io/interest/draw"><img id="todraw" src="https://lily0714.github.io/mymind.png"></a>
               </div>
            </div>
         </div>
         <div class="diy">
            <p class="post">手做</p>
            <a href="http://lily0714.github.io/手做一.png" target="_blank"><img class="post1" src="http://lily0714.github.io/手做一.png" ></a>
            <div class="dcontent">
               這是最近幾天做的桌曆。<br>
               原本是只買了計畫紙，突如其來的靈感讓我想把它變成桌曆。<br>
               這成本其實大概三十塊錢，而且封面是可以"撕下"每年做替換的。<br>
               其實上面的那兩隻小熊也是我縫的，印象中他們也陪我兩三年有了吧。<br>
               其他手做等以後再慢慢更新吧。
               <div>
               <a href="https://lily0714.github.io/interest/diy"><img id="todiy" src="https://lily0714.github.io/diyw.png"></a>
               </div>
            </div>
         </div>
          <div class="music">
            <p class="post">演奏樂器</p>
            <a href="http://lily0714.github.io/music.png" target="_blank"><img class="post1" src="http://lily0714.github.io/music.png" ></a>
            <div class="dcontent">
               高中的時候，曾經想學吉他。<br>
               但因為手太小按不好和弦，當時家裡又有烏克麗麗的玩具，於是就開始學習烏克的和弦及刷法。<br>
               靠著影片自學，漸漸學會了堪稱是"烏克麗麗界國歌"的小手拉大手。<br>
               之後，除了靠影片自學，大一也加入社團學習。<br>
               上了大學總想做點什麼特別的事，於是就又接觸了一個樂器－－口琴。<br>
               加入口琴社從一開始的複音口琴，再來和弦口琴，最後半音階口琴，<br>
               其中我感受到的一個要點是，＂不管學什麼樂器，節奏都是很重要的。＂<br>
               漸漸地，聽歌不再是只聽旋律部份，還會聽背景的鼓聲、低音部份，<br>
               藉由這種練習，我發現對演奏樂器或是唱歌都很有用，都能穩穩地跟著節奏完成一首歌。
            </div>
         </div>
         <div class="leave">
            <p class="post">留言板</p><div id="alllea" class="dcontent">
<script>
                   function store(){
                     var chk = false;
                         if(document.all("checkprivate").checked){
                            chk = true;
                         }
                      var date = new Date();
                      var now = date.getFullYear()+" - "+(date.getMonth()+1)+" - "+date.getDate()+" "+
                       date.getHours() + ':' + date.getMinutes() + ':' + date.getSeconds();
                       $.get("https://script.google.com/macros/s/AKfycbzKTZf5r656DL1NC-qNN9nVGXcnRXw7hTZiksjgg5ZrpmZk4SA/exec", {
                            "time": now,
                            "name": document.getElementById("yourname").value,
                            "leavecon": document.getElementById("leacon").value,
                            "checkprivate": chk
                      },
                        function (data) {
                            alert("Thank you for your message :D");
                        });
                        setTimeout(function(){window.location.reload();},1000);
                   }
</script>
<p style="color:#990000; font-size:14px">*目前只能留言，也只有版主看的到留言內容。<br>
版主正努力找尋方法將留言呈現在頁面上( • ̀ω•́ )</p>名字：<input class="leavecon" id="yourname" type="text"><br><br>
留言內容：<br>
<textarea class="leavecon" id="leacon" type="text" style="width: 300px;height: 150px; resize: none;"></textarea>
         <input id="checklea" type="button" value="提交" onclick="store()"><br>
<input id="checkprivate" type="checkbox">設為悄悄話
            </div>
         </div>
       </div>
       <div id="get-day"></div><script>document.getElementById("get-day").innerHTML = "今天是<br>"+ y+"年"+m+"月"+d+"日"+msg1+":D";</script>
   </div>
   <div id="FOOTER"> 
      <img src="http://lily0714.github.io/底.png" width="980" height="60">
   </div>
   </body>
