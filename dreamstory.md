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
$("#lily0714-github-io").hide();
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
height:1550px;
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
color: saddlebrown; 
} 
a:hover {  
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
               除了製圖技巧，還要會排版呢!感覺真的很困難...<br>
               所以就拿了別人提供的版型語法嘗試做修改。<br>
               雖然看的不是很懂，但看哪裡變了，就是改到哪個東西。<br>
               於是就做出了2010年第一個版型:D(也就是我在部落格供開發給大家版型的第一次)
            </div>
         </div>
         <div class="dream1">
         <br>
         <p class="post">灌溉過程 - 2009年暑假(小六升國一)</p>
            <div class="dcontent">
               還記得要升國一的那個暑假，<br>
               除了念書和補習，很多時間都沉浸在Xuite的部落格。<br>
               有時寫寫生活上發生的事，有時練習製圖。<br>
               &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 但此時製圖功力還是頗弱，就是加工後的整體圖片看起來死板板。<br>
               但有在練習就能慢慢進步，這是我一直所相信的，至少在我這領域是。<br>
               *原本想說上圖放2009年製圖的東西，但因為之前電腦重灌，可能也找不太到圖片。<br>
               *因為剛升上國一，覺得課業上要認真些，才能拿好成績，<br>
                所以2009年暑假一直到2010年暑假中間不太更新，且圖也遺失。
            </div>
         </div>
         <div class="dream1">
         <br>
         <p class="post">灌溉過程 - 2010年暑假首發第一個版型(製圖部分)</p>
            <a href="https://lily0714.github.io/2010seed2.png" target="_blank"><img class="post1" src="https://lily0714.github.io/2010seed2.png" ></a>
            <div class="dcontent">
               好不容易放暑假了，也有多一點時間做自己喜歡做的事，<br>
               所以就來更深入研究製作版型啦!<br>
               逛了許多製圖達人的網站，發現他們都是拿動漫人物的圖來做，而且圖都會發光呢!<br>
               猜想顏色是用白色的關係，但好像還有再用上什麼東西??<br>
               而且他們的圖上還有好多圖案，是要全部自己畫嗎??還是有可以下載的??<br>
               有不少人說用筆刷，那就不管它，先來試試吧!<br>
               .<br>
               可是做完以後，為什麼我只感覺到整體的圖很亂呢??到底是怎麼一回事??<br>
               而且看起來也不太有發光的感覺...<br>
               也許我能力還是不強吧，不過能做出來還是很開心呢!<br>
               待續...<br>
               *上圖為logo、頭貼和刊版(主要用於文章分類使用或是其他用途也是可以)<br>
               *網站全圖請見最上篇
            </div>
         </div>
      </div>   
   </div>
   <div id="FOOTER"> 
      <img src="http://lily0714.github.io/底.png" width="1024" height="60">
   </div>
   </body>
