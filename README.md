# json2.js使用参考

---

提供了json的序列化和反序列化方法，可以将一个json对象转换成json字符串，也可以将一个json字符串转换成一个json对象

json2.js的源码地址：

https://github.com/douglascrockford/JSON-js

---


## 使用说明


	在js文件中引用模块
	require('json2');

##序列化方法

	var jsonObj = { id: '01', name: 'Tom' };
	JSON.stringify(jsonObj);

##反序列化方法

	var jsonString = '{ "id": "01", "name": "Tom" }';
	JSON.parse(jsonString);
