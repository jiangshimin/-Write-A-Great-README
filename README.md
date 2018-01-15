# -Write-A-Great-README
grammar for markdown

Markdown语法学习（Github上README.md书写规范）
=====
Markdown 的目标是实现「易读易写」，兼容HTML。
但是，在 HTML 区块标签间的 Markdown 格式语法将不会被处理。比如，你在 HTML 区块内使用 Markdown 样式的*强调*会没有效果。也就是说，Markdown 与HTML标签不能嵌套使用

# 一、标题
![](https://upload-images.jianshu.io/upload_images/6503119-9ce0cabc320972dc.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/700)

将1~6个#井号放在标题内容的前面，就能够轻松的表示不同字号的标题。
```
 # 一级标题 字号最大
 ## 二级标题
 ### 三级标题
 #### 四级标题
 ##### 五级标题
 ###### 六级标题 字号最小
```
# 二、分割线
![](https://upload-images.jianshu.io/upload_images/6503119-1cf53b5449285a21.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/700)

使用3个以上的任意数量的`-` `_` `*` 符号，即可输出一条分割线。
```
// 以下几种情况都能够输出分割线
***
*****
____________________
----------
___
```
可以看到，图中还可以使用文字加上等号与减号分别表示一级标题与二级标题。
```
// 大于三个任意数量的等号
一级标题
======

// 大于三个任意属相的减号
二级标题
----
```
# 三、段落引用 Blockquotes
![](https://upload-images.jianshu.io/upload_images/6503119-4d921c9a099c08f3.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/700)

在普通段落前面加上一个 `>` 符号，即可将该段落标记为引用。在引用中，能够与其他任意语法组合。具体可看图中的效果。
输入一个空行，可结束一段引用。

# 四、无序列表
![](https://upload-images.jianshu.io/upload_images/6503119-16c34ce063187fa3.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/700)

`+` `-` `*` 任意一种字符与空格组合，能将一个段落标记为无序列表。无序列表中也可以与其他语法组合使用。
输入一个空行，可结束一个无序列表。

# 五、有序列表
![](https://upload-images.jianshu.io/upload_images/6503119-7ba741c507f1f22d.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/700)

任意数字与空格组合，可以开始一个有序列表。即使每一列的数字并不是按顺序来，输出结果也会智能的从1开始依次排序。
```
1. xxxxxxxx
1. xxxxx
1. xxxxxxxx

------输出结果一样-------

3. xxxxxx
2. xxxxxxxxxx
8. xxxxxxxxxxx
```
使用两行空格或者其他诸如图片这样的格式，能够终止一个有序列表。

# 六、超链接
![](https://upload-images.jianshu.io/upload_images/6503119-139a2d83c2c561af.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/700)

`[]` `()` 可以输出一个超链接。其中中括号中填写文字信息，小括号中填写链接地址信息。简书可以保留复制格式，也就是说，如果你从其他地方复制一个带超链接的文字过来，超链接会自动保留。

# 七、图片
![](https://upload-images.jianshu.io/upload_images/6503119-97650170d63cfefd.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/700)

`!` `[]` `()` 可以输出一张图片的显示。其中中括号中填写图片的描述信息，描述信息最终会在图片下方的横线中显示。小括号中填写图片的地址。
而在图片的处理上，简书的markdown做到了最人性化的体验。我们可以使用剪切工具比如QQ或者微信的剪切工具在电脑上任意剪切一张图，然后就可以直接复制在简书里。如下图所示。这一点，极大的便利了我们对图片的处理。我们不用将图片保存起来，然后拖入简书。本文中所有的图片都是剪切后直接复制进来的，简单快捷方便。大爱这个特性。

# 八、强调
![](https://upload-images.jianshu.io/upload_images/6503119-8395f4e54b32d41e.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/700)

`*`  `_` 可以设置文字为加粗或者斜体。具体使用情况见图。

# 九、代码块
![](https://upload-images.jianshu.io/upload_images/6503119-1fb36e90700c0410.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/700)

这是程序员大爱的语法。

在 `` 符号中输入文字或者代码片段，输入的文字将会被标注起来。

例如 `这是一段被标注的文字。`

代码块效果如下。
```
// 这里面支持代码高亮。
// 所以我们程序员写博客，会经常将我们的代码放在这个语法中。
// 不同的功能会显示出不同的颜色。
// 例如注释

var $element = document.querySelector('#container');
```

# 花10来分钟熟练上面这几条语句，就能够轻松的使用markdown进行README创作了。赶紧动手试试吧。













