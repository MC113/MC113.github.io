<h1>提示:</h1><br>
<h2>您当前访问的网址已失效，请前往新站</h2><br>
<p>如果你的浏览器没有自动跳转</p><a href="GOLD_GAME.html">请点这里跳转！</a>
 

<script type="text/javascript">
	window.onload = function(){
		var time = 2;
		var secondEle = document.getElementById("second");
		var timer = setInterval(function(){
			secondEle.innerHTML = time;
			time--;
			if(time==0){
				clearInterval(timer);
				location.href="http://www.mc113.github.io/GOLD_GAME.html";
