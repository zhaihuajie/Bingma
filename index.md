## Welcome to 饼码！
### 编码器
<head>
	<meta charset="UTF-8">
	<title>编码器（网页版）</title>
</head>
<body>
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
</body>
### 解码器
<head>
	<meta charset="UTF-8">
	<title>（网页版）</title>
</head>
<body>
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
</body>
### 有事练习QQ:3211718306
##### [整活，嗨害嗨](https://www.kuwo.cn/play_detail/140075087)
