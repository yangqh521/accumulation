# Markdown语法手册
## 1.粗体斜体
粗体：**粗体**
斜体：*斜体*

    粗体：**粗体**
    斜体：*斜体*
## 2.分级标题
    # 一级标题
    ## 二级标题
    ### 三级标题
## 3.外链接
[链接到百度](www.baidu.com)

    [百度](www.baidu.com)
## 4.无序列表
使用 *，+，- 表示无序列表。

* 无序列表1
* 无序列表2
* 无序列表3
+ 1
+ 2
+ 3

`* 无序列表1`<br/>
`* 无序列表2`<br/>    
`+ 1`<br/>
`+ 2`<br/>

## 5.有序列表
使用数字和点表示有序列表。
1. 有序列表1
2. 有序列表2
3. 有序列表3

    1. 有序列表1
    2. 有序列表2
    3. 有序列表3
## 6.文字引用
使用>表示文字引用
>"野火烧不尽，春风吹又生。"

    >"野火烧不尽，春风吹又生。"
## 7.行内代码块
使用 `代码` 表示行内代码块。

    `代码`
## 8.代码块
使用四个缩进空格表示代码块。

    这是一个代码块，此行左侧有四个不可见的空格。
## 9.插入图像
注意：链接中如果带有特殊符号，比如 & 需要用转义字符进行标示 \&。

![腾讯logo](http://img1.hao123.com/urlicon/6.340.png)
# Markdown进阶语法
## 1.生成目录
    在你想要生成目录的地方是用[toc]标签，就会自动在此处生成目录，
    但有些markdown编辑器不支持，如markdownPad2，你可以去网上下
    载js插件实现此功能也可以考虑使用stackedit。
## 2.内联HTML标记
<font color='red' style='font-size:20px'>红色文字</font>
`<font color='red' style='font-size:20px'>红色文字</font>`
<hr/>
<table>
    <thead>
        <tr>
            <th>第一列</th>
            <th>第二列</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>第一行</td>
            <td>文本1</td>
        </tr>
        <tr>
            <td>第二行</td>
            <td>文本2</td>
        </tr>
    </tbody>
</table>
    <table>
    <thead>
        <tr>
            <th>第一列</th>
            <th>第二列</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>第一行</td>
            <td>文本1</td>
        </tr>
        <tr>
            <td>第二行</td>
            <td>文本2</td>
        </tr>
    </tbody>
</table>
## 3.Markdown 支持以下这些符号前面加上反斜杠来帮助插入普通的符号
    \   反斜线
    `   反引号
    *   星号
    _   底线
    {}  花括号
    []  方括号
    ()  括弧
    #   井字号
    +   加号
    -   减号
    .   英文句点
    !   惊叹号