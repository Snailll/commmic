# commmic
漫画合集

2016-3-3
搜索功能 设计插件模式，面向对象设计
index.html 的 tab选项卡 采用subpage方式

主类 调用插件类的getdata()方法， 插件类使用ajax异步获取数据，并调用主类的setdata()方法将数据展示到页面。

//设计思路
class 插件名 A（主类的实例化对象 B）{
	getdata（）{
		mui.ajax(url,{
			success：{
				b.setdata();
			}
		});
	}	
}

2016-3-2
增加分类和搜索
漫画详情页添加漫画封面图片

2016-3-1
开始程序设计
index.html 中的首页
list.html
detail.html
imageviewer.html
数据来源：快看漫画app v1接口


