<!DOCTYPE html>
<html>
<head>
  <title>視傳一AB-學號-網頁版面基本架構</title>
</head>
<style>
.infor{
background-color:#DDAA00;
width:200px;
height:30px;
color:#FFFFFF;
}
h1 {
    font-family: Lobster, Monospace;
    color:#DDAA00;
  }

p {
    font-size: 16px;
    font-family: Monospace;
    color:#F0A500;
  }
  
body{
   text-align:center; border:1px double #FFF;
   background-attachment:fixed;
   background-position:50%;
   background-size:100%;
   background-repeat:no-repeat;
   background-color:#FFEE99; 
   word-wrap:break-word; 
   margin:0;
   }
h4{
   color:#D2963C;
   }
html{ 
    scrollbar-face-color:#ffffff;
    scrollbar-highlight-color:#FFEE99; 
    scrollbar-shadow-color:#FFEE99; 
    scrollbar-3dlight-color:#FFF; 
    scrollbar-darkshadow-color:#FFF; 
    scrollbar-arrow-color:#FFEE99; 
    scrollbar-track-color:#FFEE99;
    }
#banner{ 
    background-color:transparent; 
    background-repeat:no-repeat; 
    background-position:center;
    margin:5px 5px; padding:0;
   }
#title{ 
  text-align:right; 
  }
#subtitle{
   color:#DDAA00;
   }
#wrapper {
        width: 900px;   /*寬度設定為900px*/
        margin: auto;   /*版面居中對齊*/
        }
#btn {
        height:  30px; /*高度設定為  30px，此部分因為裡面的圖片自己會有高度，所以高度也不一定要設定*/
        }

#content {
        /* CSS 中 DIV 自己會長到上層 DIV100% 的寬度 (在這裡就是 #wrapper)，所以可不用設定寬度*/
        }

#footer {

         }

</style>
<img id="banner" src="https://lily0714.github.io/IMG_20170214_201651.jpg" width="700" height="400">
<h1 id="title">Welcome to this page</h1>
<p id="subtitle">這裡是lily0714的網頁</p>
<body>
<div id="wrapper"> 
  <div id="header"></div>
  <div id="btn"></div>
  <div id="content"></div>
  <div id="footer"></div>
</div>
<h3 class="infor">個人資料</h3>
<ul>
<p>是個喜歡音樂、自我矛盾很嚴重的孩子。</p>
<h4>姓名:</h4><p>陸映螢</p>
<h4>學校:</h4><p>輔仁大學</p>
<h4>學系:</h4><p>資訊工程學系</p>
<h4>生日:</h4><p> 0 7 月 1 4 日</p>
</ul>
<frameset cols="20%,30%,25%">
  <frame src="frame_a.htm">
  <frame src="frame_b.htm">
  <frame src="frame_c.htm">
</frameset>
</body>

