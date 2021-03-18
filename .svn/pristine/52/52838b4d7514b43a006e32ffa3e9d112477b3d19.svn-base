// var port ="https://m.xuematech.com/papi";
(function(){
　　var w=window.screen.width;
    console.log(w);//获取屏幕尺寸
    // alert(w)
　　var targetW=1240;//之后所有的都是按照320来做
　　var scale = w/targetW;//缩放值:当前尺寸/目标尺寸
	console.log(scale)
　　var meta=document.createElement("meta");
　　meta.name="viewport";
　　meta.content="width=device-width,initial-scale=" + scale + ",minimum-scale=" + scale;
　　document.head.appendChild(meta);
})()
var port= 'http://www.chencaiwang.com';
$(function () {
        if(($('.publicHead').html())){
                return;
        }
        $('.publicHead').load('header.html')
        $('.publicFoot').load('footer.html')
})