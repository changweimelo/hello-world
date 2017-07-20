# 移动端适配
使用rem来计算  
```<meta name="viewport" content="initial-scale=1,maximum-scale=1, minimum-scale=1">
<link rel="stylesheet" type="text/css" href="css/reset.css" />
<script type="text/javascript">     
    (function () {    
            function o(argument) {     
                document.documentElement.style.fontSize = document.documentElement.clientWidth / 7.5 + 'px';    
            }    
             var e = null;    
            window.addEventListener("resize", function () {    
                clearTimeout(e), e = setTimeout(o, 300)    
            }, !1), o()    
        })(window);    
</script>```   

