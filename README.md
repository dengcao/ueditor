# dc-UEditor 1.0.1

dc-UEditor，rich text 富文本编辑器，基于百度UEditor 1.4.3.3-utf8-php版修改。

修复了Uploader.class.php的安全隐患。

 **新增了以下功能：**

1、上传图片是否加水印。

2、新增了单独调用上传的接口。

3、表情本地化，预防百度UEditor永久停更而打不开。


### 使用方法

 **上传图片是否加水印：** 

1、打开php/config.json，将"imageWatermark"修改为true，即可开启默认添加图片水印。

2、水印图片存放位置：php/water/watermark.png。


 **单独调用上传的接口：** 

参考示例文件：demo_upload.html，里面有详细调用说明和代码实例。


### 更新说明：


1、新版1.0.1：考虑到有时候编辑的内容需要保留<span>标签，因此删除了原编辑器自动过滤<span>标签的功能。

2、使用时，调用ueditor.all.js是修改后的1.0.1版本，而调用ueditor.all.min.js是使用原自动过滤<span>标签的1.0.0版本，注意区分。


### 赞助支持：

支持本程序，请到Gitee和GitHub给我们点Star！

Gitee：https://gitee.com/dengzhenhua/ueditor

GitHub：https://github.com/dengcao/ueditor

### 关于

开发：[邓草博客 blog.5300.cn](http://blog.5300.cn)

赞助：[品络互联 www.pinluo.com](http://www.pinluo.com)  &ensp;  [AI工具箱 5300.cn](http://5300.cn)  &ensp;  [汉语言文学网 hyywx.com](http://hyywx.com)  &ensp;  [雄马 xiongma.cn](http://xiongma.cn) &ensp;  [优惠券 tm.gs](http://tm.gs)


### 接口预览

![输入图片说明](https://images.gitee.com/uploads/images/2020/0511/210952_13094c16_7397417.png "调用上传接口")



