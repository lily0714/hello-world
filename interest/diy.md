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
height:1050px;
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
         <div class="diy">
            <p class="post">手做-桌曆</p>
            <a href="http://lily0714.github.io/手做一.png" target="_blank"><img class="post1" src="http://lily0714.github.io/手做一.png" ></a>
            <div class="dcontent">
               這是最近幾天做的桌曆。<br>
               原本是只買了計畫紙，突如其來的靈感讓我想把它變成桌曆。<br>
               這成本其實大概三十塊錢，而且封面是可以"撕下"每年做替換的。<br>
               其實上面的那兩隻小熊也是我縫的，印象中他們也陪我兩三年有了吧。<br>
               其他手做等以後再慢慢更新吧。
            </div>
         </div>
         <div class="diy">
            <p class="post">手做-貓咪毛帽</p>
            <a href="http://lily0714.github.io/手做二.png" target="_blank"><img class="post1" src="http://lily0714.github.io/手做二.png" ></a>
            <div class="dcontent">
               當初看到偶像劇裡的女主戴毛帽好可愛，嫌買一頂毛帽太貴，<br>
               於是買了鉤針和毛線自己看著網路上教學做了一個。<br>
               其實一開始並不是貓咪，只是做壞意外成了貓咪!!<br>
               這樣其實也不錯啦，但還是在自家戴爽爽就好。<br>
               後來過沒幾天，就從朋友清衣服時拿到一頂毛帽，是有沒有那麼幸運阿XDD
            </div>
         </div>
      </div>   
   </div>
   <div id="FOOTER"> 
      <img src="http://lily0714.github.io/底.png" width="1024" height="60">
   </div>
   </body>
