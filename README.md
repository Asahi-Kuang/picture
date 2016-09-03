#成都北极贝科技-他乡App iOS

###Author: Asahi Kuang

###Contact: asahikuang@yahoo.com

###version 1.0v

###Create Time: 2016-09-02

-- 
####Git push symbols:
**方便git push节点查询**

`add -`  : 新增了功能、文件。

`delete -`  : 删除了功能、文件。

`update -`  : 更新（修改）了功能、文件。

`fix -`  : 修复了bug。

`modify -`  : 更改了配置、文件。

`example` : pic url


![pic url](https://github.com/Asahi-Kuang/picture/blob/master/E813B85B-773C-4FD9-B714-EC2D02A9C229.png?raw=true)

#### Annotation style:
**项目会通过使用appledoc生成文档，所以注释需要严格遵守以下格式：**

一、`.h`文件方法函数注释：
```
/**
*	@brief 		方法阐述。
*	@param 		参数名字1 参数说明1
* 	@param 		参数名字2 参数说明2
*	@return 		返回值说明
*	@warning 	警告说明
*	@exception 	方法抛出异常说明
* 	@see 			参见某个方法
* 	@bug 			漏洞说明
*/
```

二、`.m`文件方法注释：
最好采用第一点的方式，也可以用
```
/** 方法说明 */
```

三、`.h文件成员变量、枚举、结构体、block等`
采用单行注释，有多种风格：最好使用第3点风格
```
1.///注释
2.//注释
3./** 这也是单行注释 */
4./*! 同样是单行注释 */
```

四、`.m`方法内注释：
同第二点，最好使用`//`

