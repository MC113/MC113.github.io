<h1>致 玩家</h1><br>
<h2>服务器已下线，感谢您的支持</h2><br>
<p>观看旧容</p><a href="GOLD_GAME.html">请点这里</a>
 

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
