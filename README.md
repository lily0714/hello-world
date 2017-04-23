<script src="/jquery/jquery-1.11.1.min.js"></script>
<script type="text/javascript"> 
$(document).ready(function() { 
$(".interest").click(function(){
  $(".inte").toggle();
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
.post{ 
background-color:#DDAA00;
width:600px; height:30px; 
color:#FFFFFF; 
font-size:16px; 
text-align:left; 
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
.interest:hover{ 
/*滑鼠移至區塊變色*/
background: #DDAA00;
}
.in1{ 
display: none;
width: 100%;
padding: 10px 0px;
background: #efefef;
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
   <img id="banner" src="https://lily0714.github.io/IMG_20170214_201651.jpg" width="700" height="400">
  
   </div>
   <div id="WRAPPER">
      <div id="LSIDE">
          <div id="infor">
          <p class="infortitle">個人資料3</p>
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
      <p class="interest">個人興趣</p>
        <div class="inte">
         <p>畫畫</p>
         <p>出去玩</p>
         </div>
         </div>
      <div id="CONTENT">
         <h3 class="post">目前文章</h3>
         <p >目前尚未有新文章!</p>
         
      </div>
   </div>
   <div id="FOOTER"> 
      <img src="http://lily0714.github.io/底.png" width="1024" height="60">
   </div>
   </body>

