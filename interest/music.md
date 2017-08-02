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
position:relative;
left:-40px;
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
height:3250px;
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
         <div class="music">
            <p class="post">演奏樂器</p>
            <a href="http://lily0714.github.io/music.png" target="_blank"><img class="post1" src="http://lily0714.github.io/music.png" ></a>
            <div class="dcontent">
               高中的時候，曾經想學吉他。<br>
               但因為手太小按不好和弦，當時家裡又有烏克麗麗的玩具，<br>
               &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  於是就開始學習烏克的和弦及刷法。<br>
               靠著影片自學，漸漸學會了堪稱是"烏克麗麗界國歌"的小手拉大手。<br>
               之後，除了靠影片自學，大一也加入社團學習。<br>
               上了大學總想做點什麼特別的事，於是就又接觸了一個樂器－－口琴。<br>
               加入口琴社從一開始的複音口琴，再來和弦口琴，最後半音階口琴，<br>
               &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  其中我感受到的一個要點是，<br>
               ＂不管學什麼樂器，節奏都是很重要的。＂<br>
               漸漸地，聽歌不再是只聽旋律部份，還會聽背景的鼓聲、低音部份，<br>
               藉由這種練習，我發現對演奏樂器或是唱歌都很有用，都能穩穩地跟著節奏完成一首歌。
            </div>
         </div>
         <div class="music">
            <p class="post">大一上學期口琴成發 - 童話</p>
            <iframe width="400" height="300" src="https://www.youtube.com/embed/M_6XKNthRqM" frameborder="0" allowfullscreen></iframe>
            <div class="dcontent">
               童話，是我吹的第一首流行歌。<br>
               還記得在表演前我和朋友約出來練了很多次，<br>
               我們花了很多時間在練拍子，<br>
               除了去問學姐，還去找了音檔來跟它的速度。<br>
               .<br>
               大概是在比賽當天表演前30分鐘的練習時間吧，<br>
               老師發現音檔調性和我們吹的不一樣，<br>
               所以老師就用烏克麗麗幫我們伴奏。(這也是我第一次和別人合奏呢!)<br>
               這時我才發現，自己似乎已經稍微知道拍子的概念了，<br>
               和老師合了一次，不知怎麼的，好像比較不那麼擔心會吹不好。<br>
               .<br>
               這次的成發是我第一次在台上表演。<br>
               雖然在台上有些緊張，但有老師的伴奏以及朋友一起吹奏，<br>
               心裡就會覺得撐過就結束了，那也就能超越原本的自己。<br>
            </div>
         </div>
         <div class="music">
            <p class="post">大一上學期烏克麗麗成發 - Can you feel the love tonight?</p>
            <iframe width="400" height="300" src="https://www.youtube.com/embed/df_btldImSw" frameborder="0" allowfullscreen></iframe>
            <div class="dcontent">
               這首好像是獅子王的歌，聽著聽著給人一種很溫暖的感覺。<br>
               .<br>
               這次是第一次在台上表演烏克麗麗，<br>
               也是第一次彈插電的烏克麗麗:D<br>
                &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 雖然覺得彈唱應該不會彈錯，但在台上難免還是有點緊張。<br>
               而且幸好還有其他人也是彈插電的，這樣比較不那麼孤單。<br>
               再說，我們這一小家比其他小家還龐大呢!
            </div>
         </div>
         <div class="music">
            <p class="post">大一下學期烏克麗麗社遊 - 大大的擁抱</p>
            <iframe width="400" height="300" src="https://www.youtube.com/embed/NHiRtcWD2Sw" frameborder="0" allowfullscreen></iframe>
            <div class="dcontent">
               這次社遊玩了很多遊戲，<br>
               跳跳Tempo、比手畫腳、歌曲聯想、舉棋遊戲，<br>
               中午吃烤肉也好開心，<br>
               但我還是最喜歡最後的大合刷:D<br>
                &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; .<br>
                &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 在這之前，其實沒有很喜歡這首歌。<br>
               感覺跟大家一起練琴，原本不喜歡的歌都會變得喜歡了吧!<br>
               這首歌給人一種在大太陽下很開心的感覺，<br>
               所以之後的大晴天就常常讓我想到這首歌，<br>
               也經常思考這首歌的歌詞意境。
            </div>
         </div>
         <div class="music">
            <p class="post">大一下學期烏克麗麗成發 - 好想你</p>
            <iframe width="400" height="300" src="https://www.youtube.com/embed/xIV_tr3oczM" frameborder="0" allowfullscreen></iframe>
            <div class="dcontent">
               還記得，練這首歌時並沒有太多時間，<br>
               因為系上課業稍微變重了點，<br>
               &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 而且在口琴社的成發又有兩首歌要練，<br>
               原本擔心這樣會不會練不起來。<br>
               (一開始覺得"點拉打拉"有難度，還有指法的轉換也卡卡的，沒想到後來還蠻順的。)<br>
               .<br>
               我和組員一起的練習時間並不多，<br>
               所以覺得自己練的話一定要練好，才能跟上大家。<br>
               而且組員還為了這首歌去寫鼓譜，<br>
               用木箱鼓和我們合，真心覺得又是一個新體驗:D<br>
               .<br>
               最後一次合的時候，<br>
               把曲子完整的結束一次後，經過討論我們又加了一段，<br>
               讓大家以為曲子結束了，事實上並沒有XDDD
               .<br>
               這次成發一樣是彈插電的烏克，<br>
               所以心裡還是有點擔心會不會彈錯，<br>
               但似乎很順利地結束了。<br>
               只是，表演的中後段真的如我們預期，所以在台上笑了一下XDDD<br>
               *可以點影片看看我們的驚喜哦<br>
               *想知道"點拉打拉"是什麼，請去YouTube搜尋【麗麗卡拉OK】129好想你(四葉草)
            </div>
         </div>
         <div class="page">
          page 1 | <a href="https://lily0714.github.io/interest/music2">2</a> 
         </div>
      </div>
   </div>
   <div id="FOOTER"> 
      <img src="http://lily0714.github.io/底.png" width="1024" height="60">
   </div>
   </body>
