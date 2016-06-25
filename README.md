#LodopApi v1.0.0

[LODOP](http://www.mtsoftware.cn/lodop/index.html) 是一款打印插件,由于官方封装的插件异步调用时很麻烦，于是优化出了此插件，兼容amd模式

##example
	LodopApi.ready(function(LODOP){
		var printerCount = LODOP.GET_PRINTER_COUNT();
	});