## 标题
Markdown 标题支持两种形式：

### 1、用#标记

在**标题开头**加上1~6个#，依次代表一级标题、二级标题....六级标题
```
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
```
### 2、用=和-标记
在 ***标题底下*** 加上任意个`=`代表一级标题，`-`代表二级标题
```
一级标题
======

二级标题
----------
```
效果如下：
>   # 一级标题
>    ## 二级标题
>    ### 三级标题
>    #### 四级标题
>    ##### 五级标题
>    ###### 六级标题



---

## 列表
Markdown 支持有序列表和无序列表。
**无序列表使用`-`、`+`和`*`作为列表标记**
```
- Red
- Green
- Blue

* Red
* Green
* Blue

+ Red
+ Green
+ Blue
```
效果如下：
- Red
- Green
- Blue

有序列表则使用数字加英文句点`.`来表示：
```
1. Red
3. Green
2. Blue
```
效果如下：
1. Red
3. Green
2. Blue

---

## 引用
引用以`>`来表示，引用中支持多级引用、标题、列表、代码块、分割线等常规语法。

常见的引用写法：
```
> 这是一段引用    //在`>`后面有 1 个空格
> 
>     这是引用的代码块形式    //在`>`后面有 5 个空格
>
> 代码例子：
>   
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
    }

> 一级引用
> > 二级引用
> > > 三级引用

> #### 这是一个四级标题
> 
> 1. 这是第一行列表项
> 2. 这是第二行列表项
```

效果如下：
> 这是一段引用    //在`>`后面有 1 个空格
> 
>     这是引用的代码块形式    //在`>`后面有 5 个空格
>
> 代码例子：
>   
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
    }

> 一级引用
> > 二级引用
> > > 三级引用

> #### 这是一个四级标题
> 
> 1. 这是第一行列表项
> 2. 这是第二行列表项

---

## 强调
两个*或-代表加粗，一个*或-代表斜体，~~代表删除。
```
**加粗文本** 或者 __加粗文本__

*斜体文本*  或者_斜体文本_

~~删除文本~~
```
效果如下：
**加粗文本** 或者 __加粗文本__

*斜体文本*  或者_斜体文本_

~~删除文本~~

---

## 脚注(注解)
使用`[^]`来定义脚注：
```
这是一个脚注的例子[^1]

[^1]: 这里是脚注
```

效果如下：
这是一个脚注的例子[^footnot1]

---

## 图片与链接
图片与链接的语法很像，区别在一个 ! 号。二者格式：
```
图片：![]()    ![图片文本(可忽略)](图片地址)

链接：[]()     [链接文本](链接地址)
```

链接又分为行内式、参考式和 自动链接：
```
这是行内式链接：[Dwelin's Blog](http://dwelin.cn/)。

这是参考式链接：[Dwelin's Blog][url]，其中url为链接标记，可置于文中任意位置。

这是自动链接：直接使用`<>`括起来<http://dwelin.cn>

这是图片：![][avatar]

[avatar]: https://connorlin.github.io/images/avatar.jpg
```

效果如下：
这是行内式链接：[Dwelin's Blog](http://dwelin.cn/)。

这是参考式链接：[Dwelin's Blog][url]，其中url为链接标记，可置于文中任意位置。

这是自动链接：直接使用`<>`括起来<http://dwelin.cn>

这是图片：![][avatar]

[avatar]: https://connorlin.github.io/images/avatar.jpg

---

## 表格
表格对齐格式

* 居左：`:----`
* 居中：`:----:`或`-----`
* 居右：`----:`

例子：
```
|标题|标题|标题|
|:---|:---:|---:|
|居左测试文本|居中测试文本|居右测试文本|
|居左测试文本1|居中测试文本2|居右测试文本3|
|居左测试文本11|居中测试文本22|居右测试文本33|
|居左测试文本111|居中测试文本222|居右测试文本333|
```

效果如下：
|标题|标题|标题|
|:---|:---:|---:|
|居左测试文本|居中测试文本|居右测试文本|
|居左测试文本1|居中测试文本2|居右测试文本3|
|居左测试文本11|居中测试文本22|居右测试文本33|
|居左测试文本111|居中测试文本222|居右测试文本333|

--- 

## 分隔线
在一行中用三个以上的*、-、_来建立一个分隔线，行内不能有其他东西。也可以在符号间插入空格。
```
***
---
___

* * *
```

效果均为一条分割线：

***
---
___

* * *

[^footnot1]: 这里是脚注