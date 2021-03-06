## header
****
```
# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6
```

# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6

```
Header 1 的另一种表示 （===可以不用缩进对齐）
===
Header 2 的另一种表示（---一定要缩进对齐）
---
```

Header 1 的另一种表示
===
Header 2 的另一种表示
---
****

## 换行
输入两个空格，回车表示换行,也可以使用`<br>`标签<br>
## 文本样式
```
链接 :[Title](URL)  
加粗 :**Bold**  
斜体字 :*Italics*  
加粗斜体：***Bolb&Italics***  
删除线 :~~text~~  
```  
链接 :[Title](URL)  
加粗 :**Bold**  
斜体字 :*Italics*  
加粗斜体：***Bolb&Italics***  
删除线 :~~text~~  

## 分割线：\-\-\- \*\*\*   
 建议使用 \*\*\* ，\-\-\- 有其他含义，比如说 header 2，使用不当会产生其他效果，在使用 \-\-\- 时，上下需要空一行。
***
## 引用：\>
引用可以嵌套\>\>
```
>这是引用效果
  >>嵌套一个引用  
    >>>还可以嵌套

  >>嵌套对齐

>换行在对齐
```
>这是引用效果
  >>嵌套一个引用  
    >>>还可以嵌套

  >>嵌套对齐

>换行在对齐

## 缩进  
段落行首，可以用2个空格代表缩进  
## 空格   
一般情况下所有多于两个的空格都会合并成一个空格显示，要想显示多个空格可以使用下面的方法。    
```
半角空格&ensp;&#8194;两个
不断行的空格&nbsp;&#160;两个   
全角空格　　两个（shift+space space space）  
全角空格&emsp;&#8195;两个
```
半角空格&ensp;&#8194;两个  
不断行的空格&nbsp;&#160;两个   
全角空格　　两个（shift+space space space）  
全角空格&emsp;&#8195;两个

## 列表    
行首，字符：- + \* ，后面跟空格，加内容代表无序列表；  
数字 1. 跟空格，加内容代表有序列表；  
列表会自动编号，两个列表项之间空一行，可以打断列表的自动编号；  
若第一个列表项为无序列表，即使使用 1. 这种形式表现出来的也是无序列表；
若第一个列表项为有序列表，即使使用 - + \* 这种形式表现出来的也是有序列表。
```
 - 二级列表
 1. 二级列表无序
     * 三级列表
         - 四级列表
             1. 有序列表
             2. 有序列表2
             - 有序列表3
             * 有序列表4
             + 有序列表5
```

  - 二级列表
  1. 二级列表无序
    * 三级列表
      - 四级列表
        1. 有序列表
        2. 有序列表2
        - 有序列表3
        * 有序列表4
        + 有序列表5

## 图片
```
![图片名](URL)
```  
![图片名](http://upload-images.jianshu.io/upload_images/1649293-7a45cc2707a48b59.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
## 页内跳转
```
[点我跳转](#jump)
<span id="jump"/>
```
不局限与span，可以是任意一个带id属性的html标签，需要Markdown解析器支持，有的可以，有的不行。
## 脚注  
表示脚注，只要 name 不同，脚注就会有不同的编号，在文档中编号自动完成，脚注出现在文档最后。  
```
加个脚注试一下[^name]。
[^name]:第一个脚注。  
```
加个脚注试一下[^name]。
[^name]:第一个脚注。  

## 转义字符\
Markdown 中有些字符有特殊含义，比如说\*-等，在特殊的位置可以使用`\*`表示。
比如：
```
*表示斜体*
\*这不是斜体，显示星号\*
```
*表示斜体*  
\*这不是斜体，显示星号\*  
## 表格
```
| ABCD | EFGH | IJKL |
| -----|:----:| ----:|
| a    | b    | c    |
| d    | e    |  f   |
| g    | h    |   i  |
```
| ABCD | EFGH | IJKL |
| -----|:----:| ----:|
| a    | b    | c    |
| d    | e    |  f   |
| g    | h    |   i  |
## 其他
- MarkDown 支持内嵌 html,markdown 做不了的可以直接用 html 实现；
- 在特殊字符前后空行，或者加空格，有可能造成歧义，一定要严格排版。
