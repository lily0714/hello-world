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
height:3150px;
float:none;
font-family: Microsoft JhengHei;
} 
.page{
position:relative;
top:50px;
left:250px;
color:#BB5500;
font-size: 12px;
}
.page a:link{
color:#BB5500;
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
         <p class="post">灌溉過程 - 2010年暑假製作版型(二)(圖片加工部分)</p>
            <a href="https://lily0714.github.io/2010seed14.png" target="_blank"><img class="post1" src="https://lily0714.github.io/2010seed14.png" ></a>
            <div class="dcontent">
               ----續 2010年暑假製作版型(二)(圖片加工部分)---<br><br>
               這篇也是2010年暑假做的一些東西，<br>
               總覺得自己用筆刷用的很開心，<br>
               所以就一直做下去，<br>
               但還是不太知道到底要怎麼讓筆刷發光...<br>
               而且此時我發現，<br>
               我朋友的網頁變得越來越有設計感，<br>
               不太像我這樣隨便放筆刷上去。<br>
               待續...<br>
               .<br>
               *這時候除了放上一些人常用的筆刷，<br>
               也開始學習筆刷怎麼放比較好看，<br>
               也下載了很多筆刷來使用。<br>
            </div>
         </div>
         <div class="page">
         page <a href="https://lily0714.github.io/dreamstory">1</a> | 2
         </div>
      </div>   
   </div>
   <div id="FOOTER"> 
      <img src="http://lily0714.github.io/底.png" width="1024" height="60">
   </div>
   </body>
