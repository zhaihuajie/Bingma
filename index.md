## Welcome to 饼码(工具箱)！
### 常用网址
	#### [度娘](https://www.baidu.com/)
	#### [谷歌](https://google.com.hk)
	#### [VPN](https://ca.bitznet.app/#/dashboard)
		##### 我有账号，可以联系QQ领取哦！（免费15天，后面一天3角）
	#### [推特](https://twitter.com)
	#### [油管](https://youtube.com)
### 码农必备
	#### [CSDN](https://csdn.net)
	#### [零基础认领你的编程语言！](https://www.runoob.com/)
### 我们必备
	#### [英语划词必备](https://mp.weixin.qq.com/s/w60dTU8B0M8nVcME6TCIeA)
	#### [超级多的古诗词！](https://www.gushiwen.cn/)
### 编码器
<head>
	<meta charset="UTF-8">
	<title>编码器（网页版）</title>
</head>
<div>
	<input name="weibianma" type="text" placeholder="请输入未编码的字符串"><br>
	<button onclick="calc()">编码</button>
	<p></p>
</div>
<script>
	var alpha=['a','b','c','d','e','f','g','h','i','j','k','l','m','n','o','p','q','r','s','t','u','v','w','x','y','z','-','!','?',' ',','];
	var code=['.---','-.--','--.-','---.','..--','.-.-','.--.','-..-','-.-.','--..','.-..','..-.','...-','....','.///','/.//','//./','///.','..//','././','.//.','/./.','//..','.../','./..','../.','.<<<','<.<<','<<.<','<<<.','..<<','.<.<','.<<.','<..<','<.<.','<<..','.<..','..<.','...<','<<<<','.>>>'];
	function calc(){
		var input=document.getElementsByName('weibianma')[0]
		value=input.value;
		var str='';
		var len=value.length;
		var len1=alpha.length;
		for(var i=0;i<len;i++){
			for(var j=0;j<len1;j++){
				if(value[i]==alpha[j]){
					str+=code[j];
				}
			}
		}
		document.getElementsByTagName('p')[0].innerText=str;
	}
</script>
### 解码器
<head>
	<meta charset="UTF-8">
	<title>（网页版）</title>
</head>
<div>
	<input name="weibianma" type="text" placeholder="请输入未编码的字符串"><br>
	<button onclick="calc()">编码</button>
	<p></p>
</div>
<script>
	var alpha=['a','b','c','d','e','f','g','h','i','j','k','l','m','n','o','p','q','r','s','t','u','v','w','x','y','z','-','!','?',' ',','];
	var code=['.---','-.--','--.-','---.','..--','.-.-','.--.','-..-','-.-.','--..','.-..','..-.','...-','....','.///','/.//','//./','///.','..//','././','.//.','/./.','//..','.../','./..','../.','.<<<','<.<<','<<.<','<<<.','..<<','.<.<','.<<.','<..<','<.<.','<<..','.<..','..<.','...<','<<<<','.>>>'];
	function calc1(){
		var input=document.getElementsByName('weibianma')[0]
		value=input.value;
		var str='';
		var len=value.length;
		var len1=code.length;
		for(var i=0;i<len;i++){
			for(var j=0;j<len1;j++){
				if(value[i]==code[j]){
					str+=alpha[j];
				}
			}
		}
		document.getElementsByTagName('p')[0].innerText=str;
	}
</script>
### 有事QQ:3211718306
#### [整活，嗨害嗨](https://www.kuwo.cn/play_detail/140075087)
