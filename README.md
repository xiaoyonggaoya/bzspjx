# b站视频解析下载  
演示demo：https://xiaoyonggaoya.github.io/bzspjx
## 代码  
' <!DOCTYPE html>  
<html>  
<head>  
<meta charset="UTF-8">  
<meta name="viewport" content="width=device-width,initial-scale=1.0,maximum-scale=1.0,minimum-scale=1.0,user-scalable=no">  
<title>b站视频解析下载</title>  
<style>  
.main {  
  width: 70%;  
  margin: 8% auto 0;  
  background-color: #fff6;  
  padding: 2% 5%;  
  border-radius: 10px  
}  
ul {  
  padding-left: 20px;  
}  
ul li {  
  line-height: 2.3  
}  
.botton {  
    background-color:#fff;  
    border:1px solid #000;  
    text-shadow:0px 1px 0px #fff;  
    display:inline-block;  
    cursor:pointer;  
    color:#000;  
    font-family:Arial;  
    font-size:15px;  
    padding:9px 16px;  
    text-decoration:none;  
    position:relative;  
    top:1px;  
}  
@media screen and (orientation: landscape) {  
body {  
background-image:url('https://pic.imgdb.cn/item/66e8494ed9c307b7e9a72280.jpg');  
background-repeat:no-repeat;  
background-size:100%100%;  
background-attachment:fixed;  
}}  
@media screen and (orientation: portrait) {  
body {  
background-image:url('https://pic.imgdb.cn/item/66e84961d9c307b7e9a74180.jpg');  
background-repeat:no-repeat;  
background-size:100%100%;  
background-attachment:fixed;  
}}  
</style>  
</head>  
<body>  
<div class="main">  
<form action="https://xiaoyonggaona111.51server.top/b/" method="get"><div>  
<h1>b站视频解析下载</h1>  
<label><p>视频bv号：<input type="text" id="input" name="bv" value="BV1Am411y7iK"><br/></label><b>此项和av号二选一填写即可(不可省略开头的BV)</b></p>  
<label><p>视频av号：<input type="number" id="input" name="av"><br/></label><b>此项和bv号二选一填写即可，填写时省略开头的av，直接填后面的数字即可</b></p>  
<label><p>番剧ep号：<input type="text" id="input" name="ep"><br/></label><b>解析番剧用的(不支持大会员和付费番剧，不可省略开头的ep)</b></p>  
<label><p>视频的分p：<input type="number" id="input" name="p" value="1"><br/></label><b>要解析的视频分p，不填默认第1p(非分p或是b站新版合集视频请忽视此项)</b></p>  
<input class="botton" type="submit" value="提交解析">  
</div></form>  
</div>  
</body>  
</html> '
