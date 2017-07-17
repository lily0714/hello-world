<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
<script type="text/javascript"> 
$(document).ready(function() { 
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
});
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
width:500px; height:30px; 
color:#FFFFFF; 
font-size:16px; 
position:relative;
left:1px;
font-family: Microsoft JhengHei;
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
left:0px;
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
background-color:#dc7d1f;
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
font-family: Microsoft JhengHei;
} 
#CONTENT {
margin-left:200px; 
width:902px;
height:2550px;
float:none;
font-family: Microsoft JhengHei;
} 
#LSIDE { 
float:left;
width:162px; 
border-width:2px; 
border-left-style:solid; 
border-right-style:solid; 
border-bottom-style:solid; 
border-color:#DDAA00; 
font-family: Microsoft JhengHei;
}    
.icontent{
text-align:left;
font-family: Microsoft JhengHei;
}
#FOOTER { 
margin:0 auto; 
width:1024px; 
height:120px; 
}
/*超連結*/ 
a:link { 
color: white; 
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
   <img id="banner" src="http://lily0714.github.io/20170424改.jpg" width="700" height="400">
  
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
          <a href="https://github.com/lily0714" target="_blank"><img class="icon" src="https://lily0714.github.io/GitHub-Mark-32px.png" alt="lily0714"></a>
          </ul>
          </div>
      </div>
      <div id="CONTENT">
         <div class="draw">
            <br>
            <p class="post">畫畫 - 初衷</p>
            <a href="http://lily0714.github.io/畫畫1.png" target="_blank"><img class="post1" src="http://lily0714.github.io/畫畫1.png" ></a>
            <div class="dcontent">
            　<br>
               這大概是從國中就開始畫的，我都叫他小饅頭人。<br>
               一開始只是隨手畫畫，並沒有想太多，但後來他成了我一小部分的自己。<br>
               也許是長越大越覺得世界太複雜，他的存在總能時時提醒我小時候的單純。<br>
               而且我喜歡把他畫在甜點世界或是遊樂場，就像小孩一樣容易因為一些小事而開心的不得了。
            </div>
         </div>
         <div class="draw">
            <br>
            <p class="post">畫畫 - 戶外活動篇</p>
            <a href="http://lily0714.github.io/draw2.png" target="_blank"><img class="post1" src="http://lily0714.github.io/draw2.png" ></a>
            <div class="dcontent">
            　<br>
               這是高二要升高三時畫的。<br>
               也許是面臨要考學測太過煩躁，一直很想出去玩吧，只好讓小孩亂亂玩囉!<br>
               而且因為班上突然很多人在玩滑板，就會開始幻想自己滑滑板的模樣。<br>
               圖畫的很帥氣，但實際上根本就不會滑XDDD<br>
            </div>
         </div>
         <div class="draw">
            <br>
            <p class="post">畫畫 - 甜點世界篇</p>
            <a href="http://lily0714.github.io/draw3.png" target="_blank"><img class="post1" src="http://lily0714.github.io/draw3.png" ></a>
            <div class="dcontent">
            　<br>
               高中在社團開會時，突然腦中浮現一堆糖果餅乾的畫面，於是就畫出了這些。<br>
               (背。面。其。實。是。活。動。的。細。流)<br>
               除了畫出甜點，還在圖上寫了學校縮寫，是有沒有那麼無聊XDDD<br>
               當初居然還畫了疊疊樂，這整張圖大概我一輩子都忘不了吧!<br>
            </div>
         </div>
         <div class="draw">
            <br>
            <p class="post">畫畫 - 瑪力歐世界篇</p>
            <a href="http://lily0714.github.io/draw4.png" target="_blank"><img class="post1" src="http://lily0714.github.io/draw4.png" ></a>
            <div class="dcontent">
            　<br>
               這應該也是在社團開會時畫的(因為背面還是活動細流XDD)，<br>
               但我真的想不起來為什麼要畫這個，可能真的很喜歡瑪力歐吧:D<br>
               每次拿到無敵星星，總希望就這樣玩到關卡的終點，<br>
               因為就可以拉旗子了，還不用遭受食人花攻擊。<br>
               另外，其實我比較喜歡騎著耀西(龍)玩，牠真的很可愛:D
            </div>
         </div>
         <div class="draw">
            <br>
            <p class="post">畫畫 - 童話世界篇(傑克與魔豆)</p>
            <a href="http://lily0714.github.io/draw5.png" target="_blank"><img class="post1" src="http://lily0714.github.io/draw5.png" ></a>
            <div class="dcontent">
            　<br>
               這是在背單字背到很煩時畫的。<br>
               其實原本是想模仿線上遊戲中的場景畫整顆藤蔓樹，<br>
               然後畫出樹後忽然又想玩盪鞦韆，<br>
               於是兩者就結合了XDDD
            </div>
         </div>
      </div>   
   </div>
   <div id="FOOTER"> 
      <img src="http://lily0714.github.io/底.png" width="1024" height="60">
   </div>
   </body>
