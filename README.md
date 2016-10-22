# layout
块状元素 上下左右居中：  
使用方法：  
position:absolute  +  top:50%  +  left:50% （top/left百分比是相对于最近定位 父元素 的 高/宽 计算的）  
搭配（根据具体情况 以下二选一）：  
1. 需要居中的块状元素 宽高确定：margin-top:height/2;  margin-left:width/2;  
2. 宽高不确定：transform: translate3d(-50%,-50%,0);  
