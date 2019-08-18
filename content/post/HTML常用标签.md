---
title: "HTML常用标签"
date: 2019-08-18T12:11:31+08:00
draft: false
---

# HTML常用标签

## a标签的用法

a标签有2个常用的标签属性

* href，hyper+reference     超链接

* target，在哪个窗口打开href的超链接

a标签href的取值

* 网址：https://baidu.com;http//baidu.com;//baidu.com;最后一种权限最高，建议使用这种输入方式

* 路径：/a/b/c;a/b/c;  index.html;./index.html

* 伪协议：javascript:代码;(案例：javascript:alert(1);做一个a标签，这个标签什么也不做)；    mailto:邮箱;       tel:电话;

* ID:   href =#xxx   跳转到xxx

a标签target的取值

内置名字

* _blank    在空白（新的）界面打开
  
* _top      所有iframe（界面）最顶层打开

* _parent   副级窗口，在当前链接（界面）的上一层打开

* _self     在自己的界面打开

## img标签的用法

img(图片)标签，作用是发出get请求，展示这个图片

属性

* src       source，资料，接图片地址

* alt       可选填

* height    高
 
* width     宽

* 默认代码格式: <img src="图片" alt ="介绍">

事件

* onload    在加载成功时显示一个介绍，提示用

* onerror   监听图片是否加载成功，可以做一个补救方案，xxx.src="./404.png"

响应式

* max-width：100%; 让图片的宽始终是页面大小，适配手机

## table标签的用法

table相关标签

* table         表格
  
* thead         表格的头部

* tbody         表格的中间部分
  
* tfoot         表格的尾部
  
* tr            table+row，table里的一行
  
* th            表头

* td            table+data，表格里的数据
  
相关样式

* table-layout ：auto ; 默认值，自动计算行的宽，高，自动对齐     
             
               ：fixed; 尽量平均宽和高

* border-collapse ：collapse;合并表格
  
* border-spacing：0;控制border之间的距离为0 
  
## form标签的用法

form（表单）标签，作用是发送get或post请求，刷新界面（提交）

属性

* action         控制请求哪个界面，里面写什么就访问什么地址
  
* autocomplete   是否自动填充，多用于登陆时保存登陆信息
  
* method         选择用get或post请求
  
* target         把哪个页面变成yyy页面

事件

* onsubmit

* 一个表单必须有（type=“submit”） 这个表单才可以提交

## input标签的用法

input标签的作用：让用户输入内容

属性：类型type：

* name        重点使用，给文本框的属性加一个名字，方便分类文本框 

* text        文本
  
* color       颜色
  
* password    不展示具体内容，例如输入密码让字符隐藏起来********
  
* radio       单选框:o男 o女  加入相同的name才能单选
 
* button      定义一个按钮，里面可以加各种文字，照片，链接
  
* checkbox    多选框，用同一个name表示一个组的
  
* file        上传文件   <input type="file" multiple>可以上传多个文件
  
* submit      提交，刷新（按钮）必须有的属性
  
* hidden      上传看不见的内容，可以让js自动填充一个字符串，id之类的

* number      可以在文本框里自己选择填写的数据
  
* search      可以直接在文本框删除内容
  
* tel         电话
  
* email       邮件

其它输入标签

* select+option   选择标签， 例如:选择星期几

  <select>  是真正的值  用户看见的值

    <option value ="">--请选择--</option>

    <option value ="1">星期一</option>

    <option value ="2">星期二</option>

   </select)

* textarea    输入多行内容，文本框可以拖动大小
  
  textarea style = "resize : nome; width = 50%; height = 200px; "

    </textarea>                     固定宽高，不能拖动文本框，改变大小

事件

* onchange      输入改变时触发
  
* onfocus       把鼠标放在上面时触发

* onblur        鼠标从里面移出来时触发

重点：input和button的区别

* <input type ="submit" value ="搞起"/)
  
    input里面不能有其它内容

* <button type ="submit">搞起</button)

    button里可以添加任意内容，图片之类的

HTML,新增了验证器功能

学习体会

HTML标签数量很多，但经过分类学习，自己在vscode上进行了操作演练，对这些标签的属性和用法有了大概的了解，只是使用上有点不熟悉，已经做好学习笔记，会经常拿出笔记进行背诵。

期待下节课学习制作简单点的网页，把学到的知识使用起来。

