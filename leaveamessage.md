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
$("#checkprivate").attr("checked",'');
</script>
 <link href="insidepage.css" rel="stylesheet" type="text/css" media="all"> 
<style>
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
         <div id="showcon">
         <script>
           $(function(){
            var $show = $('#showcon');
            $.get("https://script.google.com/macros/s/AKfycbxrFeNhRqzjgSPRqYXBYl12muN71Y3OfZEubLOs81rgwPxaoHs/exec", {
                            "row": 2,
                            "col": 1
                      },function(data){
                          var d = data.split(',');  //把傳出來的字串分割成陣列
                          var arr = [];  
                          for(var i=0; i<lastrow; i++){
                          arr[i] = d.splice(0, lastcol); 
                          $show.append(arr[i]+'<br/>');
                        });
         </script>
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
                            "checkprivate":chk
                        },
                        function (data) {
                            alert("Thank you for your message :D");
                        });
                   }
</script>
<p style="color:#990000; font-size:14px">*目前只能留言，版主正努力找尋方法將留言呈現在頁面上( • ̀ω•́ )</p>名字：<input class="leavecon" id="yourname" type="text"><br><br>
留言內容：<br>
         <textarea class="leavecon" id="leacon" type="text" style="width: 300px;height: 150px; resize: none;"></textarea>
         <input id="checklea" type="button" value="提交" onclick="store()"><br>
<input id="checkprivate" type="checkbox">設為悄悄話
            </div>
         </div>
      </div>   
   </div>
   <div id="FOOTER"> 
      <img src="http://lily0714.github.io/底.png" width="980" height="60">
   </div>
   </body>
