# demo1
!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<link rel="stylesheet" type="text/css" href="index.css">
	<title>demo</title>
</head>
<body>
   <div class=box0>
     		<p><br/><br/>Joe Smith</p>
   		<p>123456678@163.com</p>
   	</div>
   <div class="box1"><a href="http://www.baidu.com">百度</a></div>
   <div class="box2"><a href="http://www.taobao.com">淘宝</a></div>
   <div class="box3"><a href="http://www.shufe.com">上财门户</a></div>
   <img src="d:\Users\admin\Desktop\1_副本.jpg">
</body>
</html>
box0{
	font-size: 40px;
	height:350px;
	width:1350px;
	background-color:green;
	text-align: center;
    
}

 .box1,.box2,.box3{
	height :100px;
	line-height: 100px;
	width:1350px;
	border-bottom:1px solid black;
	font-size: 30px;
	font-color:red;
}

.box1:hover,.box2:hover,.box3:hover{
	background-color:grey;
}

.box3{
	position:absolute;
	bottom:0;
}
.box2{
    position: absolute;
    bottom:100px;
}
.box1{
	position: absolute;
    bottom:200px;
}

img{
	position:relative;
	bottom:300px;
	left:300px;
	border-radius: 200px 200px;
}
