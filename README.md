<script src="http://ajax.googleapis.com/ajax/libs/jquery/1.9.1/jquery.min.js"></script>
<script type="text/javascript"> 
$(document).ready(function() { 
$("p.interest").css({cursor:"pointer"}).click(function(){
  $(".in1").slideToggle("slow");
  $(".in2").slideToggle("slow");
  $(".in3").slideToggle("slow");
});
$("p.in1").css({cursor:"pointer"}).click(function(){
  $(".post1").fadeToggle("fast");
  $(".draw").fadeToggle("fast");
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
.post1{ 
background-color:#DDAA00;
width:100px; height:30px; 
color:#FFFFFF; 
font-size:12px; 
text-align:left; 
}
.draw{
display: none;
text-align:left; 
}
.draw1{
width:100%;
height:auto;
}
p { 
font-size: 12px; 
font-family: Monospace; 
color:#BB5500; 
text-align:center;
} 
body{ 
text-align:center; 
double #FFF; 
background-color:#FFEE99; 
word-wrap:break-word; 
margin:0; 
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
height:520px;
/*border-width:2px;
border-left-style:solid; 
border-right-style:solid; 
border-bottom-style:solid; 
border-color:#DDAA00;*/ 
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
   <div id="bantitle">
   <img id="banner" src="http://lily0714.github.io/20170424改.jpg" width="700" height="400">
  
   </div>
   <div id="WRAPPER">
      <div id="LSIDE">
          <div id="infor">
          <p class="infortitle">個人資料</p>
          <img src="http://lily0714.github.io/IMG_20161102_213309.jpg" width="145" height="249">
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
           <p class="in2">出去玩</p>
           <p class="in3">手做</p>
        </div>
      </div>
      <div id="CONTENT">
         <h3 class="draw post1">畫畫</h3>
          <img class="draw draw1" src="http://lily0714.github.io/畫畫1.png" >
         　<p class="draw">這大概是從國中就開始畫的，我都叫他小饅頭人。</p>
          <p class="draw">一開始只是隨手畫畫，並沒有想太多，但後來他成了我一小部分的自己。</p>
          <p class="draw">也許是長越大越覺得世界太複雜，他的存在總能時時提醒我小時候的單純。</p>
          <p class="draw">而且我喜歡把他畫在甜點世界或是遊樂場，就像小孩一樣容易因為一些小事而開心的不得了。</p>
      </div>
   </div>
   <div id="FOOTER"> 
      <img src="http://lily0714.github.io/底.png" width="1024" height="60">
   </div>
   </body>

