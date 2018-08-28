---
title: markdown语法 #文章标题
date: 2018-08-28 10:46:25
tags:  #文章标题
- markdown
- 教程
categories: #文章分类
- 语法
cover_picture:  images/1.jpg
---
# 标题
-------
标题分为一到六级，分别为1~6个#，#后面需要带上一个空格·· 

# 引用
写法一：
单行式引用
> 书是人类进步的阶梯
别看了其实只有上面这一句

写法二：
> 书是人类进步的阶梯
> 别看了其实只有上面这一句

嵌套引用：
> 天王盖地虎
>> 小鸡炖蘑菇
>>> 宝塔镇河妖
>>>> 蘑菇放辣椒

# 代码块
下面是一段js代码：
```javascript
for(var i = 0； i < 10; i++){
    console.log(i);
}
```

下面是css代码
```css
body{
    color:red;
    font-size:12px;
}
```

# 超链接
[点我](http://www.baidu.com)跳转到百度

# 图片
#引入图片
```
引入图片方法： ！[图片名字](图片链接)
```

![表情包](http://img0.imgtn.bdimg.com/it/u=1686462020,2188330230&fm=214&gp=0.jpg)
#图片超链接


[![表情包](http://img0.imgtn.bdimg.com/it/u=1686462020,2188330230&fm=214&gp=0.jpg)](http://www.baidu.com)

```

# 列表
## 有序列表
1. 手机
2. 电脑
3. pad

## 无序列表
* 小米
* 华为
* 魅族

# 表格

姓名|排行|特长
-|-|-
刘备|老大|哭
关羽|老二|打
张飞|老三|骂