# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
段落内容
段落内容
**粗体字**
*斜体字*
~~删除线~~
***粗体和斜体***

## 块引用
> 块引用

## 具有多个段落的块引用
> 块引用
>
> 块引用

## 嵌套快引用
> 块引用
>
> > 嵌套块引用

## 具有其他元素的快引用
> #### The quarterly results look great!
>
> - Revenue was off the chart.
> - Profits were higher than ever.
>
>  *Everything* is going according to **plan**.

## 有序列表
1. First item
2. Second item
3. Third item
4. Fourth item

## 缩进有序列表
1. First item
2. Second item
3. Third item
    1. Indented item
    2. Indented item
4. Fourth item

## 无序列表
- First item
- Second item
- Third item
- Fourth item

## 缩进无序列表
- First item
- Second item
- Third item
    - Indented item
    - Indented item
- Fourth item

## 在列表中添加元素
要在保留列表连续性的同时在列表中添加另一个元素，请将该元素缩进四个空格或一个制表符，如以下示例所示。

### 段落
*   This is the first list item.
*   Here's the second list item.

    I need to add another paragraph below the second list item.

*   And here's the third list item.

### 快引用
*   This is the first list item.
*   Here's the second list item.

    > A blockquote would look great below the second list item.

*   And here's the third list item.

### 代码块
代码块通常缩进四个空格或一个制表符。当它们在列表中时，将它们缩进八个空格或两个选项卡。
1.  Open the file.
2.  Find the following code block on line 21:

        <html>
          <head>
            <title>Test</title>
          </head>

3.  Update the title to match the name of your website.

### 图片
1.  Open the file containing the Linux mascot.
2.  Marvel at its beauty.

    ![Tux, the Linux mascot](/assets/images/tux.png)

3.  Close the file.

### 表格
|表头1|表头2|表头3|
|---|---|---|
|内容|内容|内容|
|内容|内容|内容|
|内容|内容|内容|

### 代码
要将单词或短语表示为代码，请将其括在勾号（`）中。
At the command prompt, type `nano`.

### 转义刻度线
如果要表示为代码的单词或短语包含一个或多个刻度线，可以通过将单词或短语括在双刻度线（``）中来对其进行转义。
``Use `code` in your Markdown file.``

### 代码块
要创建代码块，请在代码块的每一行缩进至少四个空格或一个制表符。
    <html>
      <head>
      </head>
    </html>

### 水平线
要创建水平线***，请单独在一行上使用三个或更多的星号（），破折号（---）或下划线（___）。
***
---
_____________

### 链接
要创建链接，请将链接文本括在方括号（例如[Duck Duck Go]）中，然后立即在URL后面加上括号（例如(https://duckduckgo.com)）中的URL 。
My favorite search engine is [Duck Duck Go](https://duckduckgo.com).

### 添加标题
您可以选择为链接添加标题。当用户将鼠标悬停在链接上时，这将显示为工具提示。要添加标题，请将其括在URL后面的括号中。
My favorite search engine is [Duck Duck Go](https://duckduckgo.com "The best search engine for privacy").

### 网址和电子邮件地址
要将URL或电子邮件地址快速转换为链接，请将其括在尖括号中。
<https://markdown.p2hp.com>
<fake@example.com>

### 格式化链接
为了强调链接，请在方括号和括号之前和之后添加星号。
I love supporting the **[EFF](https://eff.org)**.
This is the *[Markdown Guide](https://markdown.p2hp.com)*.


### 参考样式链接
引用样式链接是一种特殊的链接，它使URL在Markdown中更易于显示和阅读。引用样式的链接分为两部分：与文本保持内联的部分以及在文件中其他位置存储的部分，以使文本易于阅读。

格式化链接的第一部分
参考样式链接的第一部分使用两组括号进行格式化。第一组方括号包围应显示为链接的文本。第二组括号显示了一个标签，该标签用于指向您存储在文档其他位置的链接。

尽管不是必需的，但您可以在第一组和第二组支架之间包含一个空格。第二组括号中的标签不区分大小写，可以包含字母，数字，空格或标点符号。

这意味着以下示例格式对于链接的第一部分大致相同：
[hobbit-hole][1]
[hobbit-hole] [1]

格式化链接的第二部分
引用样式链接的第二部分使用以下属性设置格式：

标签放在方括号中，后紧跟冒号和至少一个空格（例如[label]: ）。
链接的URL，您可以选择将其括在尖括号中。
链接的可选标题，您可以将其括在双引号，单引号或括号中。
这意味着以下示例格式对于链接的第二部分几乎都是等效的：

[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle
[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle "Hobbit lifestyles"
[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle 'Hobbit lifestyles'
[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle (Hobbit lifestyles)
[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Hobbit lifestyles"
[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> 'Hobbit lifestyles'
[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> (Hobbit lifestyles)

您可以将链接的第二部分放在Markdown文档中的任何位置。有些人将它们放在出现的段落之后，而其他人则将它们放在文档的末尾（例如尾注或脚注）。

### 转义字符
要显示原义字符，否则将用于设置Markdown文档中的文本格式\，请在字符前面添加反斜杠（）。

\* Without the backslash, this would be a bullet in an unordered list.


