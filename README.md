<!--
     ____ _  __ __  __ __ __ ____
    /  _// |/ // / / // //_// __ \
   _/ / /    // /_/ // ,<  / /_/ /
  /___//_/|_/ \____//_/|_| \____/

-->
<!DOCTYPE html>
<html lang="zh-CN">
<head>
	<meta charset="UTF-8">
    <meta http-equiv="Cache-Control" content="no-transform">
    <meta http-equiv="Cache-Control" content="no-siteapp">
    <meta name="viewport" content="width=device-width,initial-scale=1,maximum-scale=1">
    <meta name="robots" content="noindex, nofollow" />
    <link rel="icon" type="image/x-icon" href="https://cdn.jsdelivr.net/gh/xb2016/kratos-pjax@0.4.0/static/images/favicon.ico">
    <title>念我无她</title>	

	<style>
	 *{box-sizing:border-box}
    a,a:hover{text-decoration:none}
    body{margin:0;padding:0;color:#324e63;font-family:Quicksand,sans-serif}
    .min{display:flex;padding:50px 20px;width:100%;height:auto;min-height:100vh;background-image:url(https://cdn.jsdelivr.net/gh/Moe-dog/prprpr.love@0.6/statics/img/1.jpg);background-position:center;background-size:cover;background-repeat:no-repeat;background-attachment:fixed}
    #min-box{position:relative;margin:auto;width:20pc;max-width:700px;border-radius:9pt;background:rgba(255,255,255,.44);box-shadow:0 8px 60px -10px rgba(13,28,39,.6)}
    #min-img{position:relative;z-index:4;overflow:hidden;margin-right:auto;margin-left:auto;width:150px;height:150px;border-radius:50%;background:rgba(255,255,255,.44);box-shadow:0 5px 50px 0 #ddd,0 0 0 7px rgba(255,255,255,0);transform:translateY(-50%)}
    .min-card{margin-top:-35px;padding:0 20px;padding-bottom:40px;text-align:center;transition:all .3s}
    .min-name{margin-bottom:15px;color:#333;font-weight:700;font-size:24px}
    .min-txt{margin-bottom:15px;color:#324e63;font-weight:500;font-size:18px}
    .min-button{display:flex;margin-top:40px;justify-content:center;align-items:center}
    .min-Jump{margin:15px 35px;margin-right:0;margin-left:0;padding:15px 40px;min-width:201px;min-height:55px;border:none;border-radius:50px;background:linear-gradient(45deg,#1da1f2,#0e71c8);box-shadow:0 4px 30px rgba(19,127,212,.4);color:#fff;font-weight:700;font-size:19px;cursor:pointer;transition:all .3s;backface-visibility:hidden}
    .min-Jump:focus{outline:0!important}
    .min-Jump:hover{transform:translateY(-5px)}
    #Seconds{margin-top:30px;color:#000;text-align:center;font-size:68px}
    @media screen and (max-width:767px){.min{padding-top:75pt;height:auto;min-height:100vh;}.min-Jump{margin:15px 25px;min-width:170px;}#Seconds{margin-top:20px;}}
    @media screen and (max-width:576px){#min-img{width:90pt;height:90pt;}#min-box{width:100%;}.min-button{flex-wrap:wrap;}.min-Jump{margin:0;margin-bottom:1pc;width:100%;max-width:300px;min-width:inherit;}.min-Jump:last-child{margin-bottom:0;}}
		</style>
</head>
<body>
 <div class="min">
      <div id="min-box">
        <div id="min-img">
          <div id="Seconds"></div>
        </div>
        <div class="min-card">
          <div class="min-name">正在重定向</div>
          <div class="min-txt">本站域名已更换，请更新访问地址</div>
          <div class="min-button"> 
            <a class="min-Jump"  href="https://www.gas7.cn/">立即前往</a>
          </div>
        </div>
      </div>
    </div>
    <script>
      var t = 5;
      document.getElementById("Seconds").innerHTML = t;
      setInterval(function(){
        if(t == 0){
          location.href = "https://www.gas7.cn/";
          t -= 1;
        }else if(t > 0){
          t -= 1;
          document.getElementById("Seconds").innerHTML = t;
        }
      },970)
    </script>
</body>
</html>
