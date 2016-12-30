# Github Markdown Syntax
Github 有一些自己扩展的 Markdown 语法：
> GitHub.com uses its own version of the Markdown syntax that provides an additional set of useful features, 
> many of which make it easier to work with content on GitHub.com.

## USERNAME @MENTION
> Typing an    @   symbol, followed by a username, will notify that person to come and view the comment. 
> This is called an “@mention”, because you’re mentioning the individual. You can also @mention teams within an organization.

```
Contact Me: @WeihanLi
```

你可以使用 "@" 符号后加上 用户名来提醒这个用户来看这个评论，这通常被叫做 【@mention】（类似微博中的 @）,因为你正提及到某个个体，你也可以
在 "@" 后加一个组织名称来提醒一个团队。

## ISSUE REFERENCES 
> Any number that refers to an Issue or Pull Request will be automatically converted into a link.

任意引用一个 Issue 或 Pull Request 的数字会自动转换为一个链接。

```
#1

MvcSimplePager#1

WeihanLi/MvcSimplePager#1
```

#1

MvcSimplePager#1

WeihanLi/MvcSimplePager#1

## EMOJI
> To see a list of every image we support, check out [www.emoji-cheat-sheet.com](http://www.emoji-cheat-sheet.com)

Github 扩展的 markdown 语法支持 emoji ，你可以在  [www.emoji-cheat-sheet.com](http://www.emoji-cheat-sheet.com) 上看到一个
完整的 Github markdown 语法支持的 emoji 图片

```
GitHub supports emoji!
 :+1: :sparkles: :camel: :tada: :rocket: :metal: :octocat: 
```

GitHub supports emoji!

 :+1: :sparkles: :camel: :tada: :rocket: :metal: :octocat: 

## FENCED CODE BLOCKS
> Markdown coverts text with four leading spaces into a code block; 
> with GFM you can wrap your code with  ```  to create a code block without the leading spaces. 
> Add an optional language identiﬁer and your code with get syntax highlighting.

Markdown 会将带有4个前导空格的文本转换为一个代码块。

你可以使用 GFM(Github Flavored Markdown 【Github支持的Markdown】)语法，在你的代码的外部用 “ ``` ”包含起来，这样就不需要前导空格了。
 
你可以添加一个可选的语言标识符来使你的代码高亮。

>       ``` javascript 
>       function test() { 
>         console.log("look ma’, no spaces"); 
>       }
>        ```

``` javascript 
function test() { 
  console.log("look ma’, no spaces"); 
}
 ```

## TASK LISTS
```
- [x] this is a complete item 
- [ ] this is an incomplete item 
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported 
- [x] list syntax required (any unordered or ordered list supported)
```

- [x] this is a complete item 
- [ ] this is an incomplete item 
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported 
- [x] list syntax required (any unordered or ordered list supported)

## TABLES
> You can create tables by assembling a list of words and dividing them with hyphens    -    (for the ﬁrst row), 
> and then separating each column with a pipe    | :

您可以用管道和连字符标识符来创建一个表格。
连字符用来创建每个列标题（针对第一行），用管道分隔每个列

```
First Header | Second Header 
------------ | ------------
Content cell 1 | Content cell 2 
Content column 1 | Content column 2
```

First Header | Second Header 
------------ | ------------
Content cell 1 | Content cell 2 
Content column 1 | Content column 2
