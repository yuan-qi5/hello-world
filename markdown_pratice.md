**标题** 
======

#    一级标题
##   二级标题
###  三级标题

一级标题
======
二级标题
------

注 ： 用一个空格在 # 和标题之间进行分隔

**段落**
=====
要创建段落，使用空白行将一行或者多行文本进行分隔。

example : 
I really like using Markdown.

I think I'll use it to format all of my documents from now on.

I really like using Markdown  
I think I'll use it to format all of my documents from now on.

I really like using Markdown.<br>
I think I'll use it to format all of my documents from now on.

换行
=====
结尾空格(通过两个或多个空格进行换行)，或者结尾添加<br>

**强调**
======
粗体 ：通过在文本前后各添加两个星号 * 或下划线 _ ,推荐使用星号 * <br>
粗体 **粗体** __粗体__

斜体 ： 在文本前后各添加一个星号或下划线，推荐使用星号 <br>
斜体 *斜体* _斜体_

同时使用粗体和斜体 推荐使用三个星号 <br> 
***粗斜体***

**引用**
======
块引用 ： 通过 > 创建 <br>
**多个段落的块引用**通过为空白行添加 > 实现
> I really like using Markdown .
>
> I'll often use it .

**嵌套块引用**通过 >> 实现
> I really like using Markdown .
>
>> I'll often use it

**带有其他元素的块引用**  <br>
块引用可以包含其他 Markdown 格式的元素，但并非所有元素都可以使用，需要进行实验以查看那些有效 <br>
> ### 标题
> **粗体** *斜体* ***粗斜体***

**列表**
=======
**有序列表** : 在每个列表项前添加数字并紧跟一个英文句点，数字不必按数学顺序排列，但列表应以数字 1 起始<br>
example : <br>
1. first item
2. second item
3. third item

**无序列表** ： 在列表项前添加破折号-、星号*、或加号+。缩进一个或多个列表项可创建嵌套列表。
- first item
- second item
- third item
  
note : 选择一种符号并坚持下去，不要混用

**在列表中嵌套其他元素** ： 要在保留列表连续性同时在列表中添加另一种元素，请将该元素缩进四个空格或一个制表符（如段落、引用块）。若要嵌入代码块、列表（本身采用四个空格或一个制表符缩进），则缩进八个空格或两个制表符。 <br>
example : <br>
1. first item
2. second item
3. third item
    - indented item
    - indented item
4. fourth item

**代码**
======
要将单词或短语表示为**代码**，请将其包裹在反引号中 <br>
example : <br>
At the command prompt, type `nano`. <br>

转义反引号 ：   <br>
要表示为代码的单词或短语中包含一个或多个反引号，则可以通过将单词或短语包裹在双反引号中 <br>
example :   <br>
`` Use `code` in your Markdown file .``

代码块 ： 要创建代码块，请将代码块的每一行缩进至少四个空格或一个制表符(github识别不出？), 用三个反引号即可  
example :  
``` python
  print("hello world")   
  print("world hello")
```

**分隔线**
======
要创建分割线，请在单独一行上使用三个或多个 *** , 破折号 --- ，或下划线 ___ ,并且不能包含其他内容。  
为了兼容性，请在分割线前后均添加空白行。   

---

***

___

**链接**
=====
链接放在中括号内，链接地址放在后面的括号中，链接 title 可选   
超链接 Markdown 语法代码 : `[超链接显示名](超链接地址 '超链接 title')`   
example :   
这是一个链接 [Markdown 语法](https://markdown.com.cn 'Markdown 教程')    

带格式化的链接    
**强调**链接 ： 在链接的语法前后增加星号    
要将链接表示为**代码**，在方括号中添加反引号    
example :    
I love deepseek **[deepseek](https://chat.deepseek.com/ 'deepseek 官网')**    
This is the gpt [`gpt`](https://chatgpt.com/ 'gpt 官网')    

**引用类型链接**    

使 URL 在 Markdown 中更易于显示和阅读。参考样式链接分为两部分 ： 与文本保持内联的部分以及存储在文件中其他位置的部分，以使文本易于阅读     

第一部分格式 ： `[显示为链接的文本][标签 : 用于指向存储在文档其他位置的链接]` (可在两组间包含个空格，第二组括号中的标签不区分大小写)     

第二部分格式 : `[标签]: 链接的 URL (链接的可选标题)`    

example :    
[chatgpt][1]  

[1]:https://chatgpt.com/ 'gpt官网'    

note : 为兼容性，请在 URL 中空格用 %20 代替，两个部分之间一定要有空行

图片
=======
插入图片 Markdown 语法 : `![图片alt](图片链接 "图片title")` title 可选

链接图片 ： 给图片增加链接 <br>
将图像的 Markdown 括在方括号中，然后将链接添加在圆括号中。 <br>
`[![图片alt](图片链接 "图片title")](https://markdown.com.cn)`

转义字符语法
=======
通过反斜杠     
\* Without the backslash, this would be a bullet in an unordered list.

特殊字符自动转义 : & <    
&copy  <br>
AT&T  <br>
4 < 5

内嵌 HTML 标签
========
留个坑，因为现在不会 HTML 语法 qwq

























