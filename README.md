# pagination  

[CODEPEN](https://codepen.io/justin000abc/pen/gOYQpOb)

使用方法：  
new Pagination({  
 o: $('.item_wrap'), //要執行分業的元素的父框架  
 page: 1, //起始頁  
 pages: 8, //每頁的數量  
 is_scroll: false, //點擊後是否捲動到.go的位置  
 lazy: false, //是否啟動lazyload  
 callback: {  
 page_hash: function(i){  
 //點擊頁碼後執行的callback，可在這控制location.hash  
 location.hash = '#'+ (i+1);  
 }  
 }  
});  

