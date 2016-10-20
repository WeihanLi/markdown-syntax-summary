# 文本
> 一个 Markdown 段落是由一个或多个连续的文本行组成，它的前后要有一个以上的空行 （空行的定义是显示上看起来像是空的，便会被视为空行。比方说，若某一行只包含空格 和制表符，则该行也会被视为空行）。普通段落不该用空格或制表符来缩进。  
> 如果想要依赖 Markdown 来插入 `<br />` 标签的话，在插入处先按入两个以上的空 格然后回车。

>   ```
>       AAA BBB 
>       CCC  
>       DDD
>   ```

AAA BBB 
CCC  
DDD

> 如果要标记一小段行内代码，你可以用反引号把它包起来(`)
>
>   ```
>       I love C#,C# Programing language output "HelloWorld",`Console.WriteLine("HelloWorld");`.So beautiful!
>   ```

I love C#,C# Programing language output "HelloWorld",`Console.WriteLine("HelloWorld");`.So beautiful!
> 如果要在代码区段内插入反引号，你可以用多个反引号来开启和结束代码区段：
>
>   ```
>       Example as follows: ``There is a literal backtick (`) here.`` Interesting!  
>       A single backtick in a code span: `` ` ``  
>       A backtick-delimited string in a code span: `` `foo` ``   
>   ```

Example as follows: ``There is a literal backtick (`) here.`` Interesting!  
A single backtick in a code span: `` ` ``  
A backtick-delimited string in a code span: `` `foo` ``   

> Markdown 使用星号（*）和底线（_）作为标记强调字词的符号，被 * 或 _ 包围的字词会 被转成用 \<em> 标签包围，用两个 * 或 _ 包起来的话，则会被转成 \<strong>
>
>   ```
>       *ABC*
>       _ABC_
>       **ABC**
>       __ABC__
>   ```

*ABC*  
_ABC_  
**ABC**  
__ABC__


# 特殊字符
>   ```
>       &copy;  
>       &gt;  
>       &lt;  
>       &amp;  
>       AT&amp;T 
>       4&lt;5
>   ```

&copy;  
&gt;  
&lt;  
&amp;  
AT&amp;T   
4&lt;5


# 标题
>   ## 标题语法
>   Markdown 支持两种标题的语法，类 Setext 和类 atx 形式。  
>   &nbsp; 类 Setext 形式是用底线的形式，利用 =（最高阶标题）和 -（第二阶标题   
>   &nbsp; 类 Atx 形式是在行首插入1到6个# ，对应到标题1到6


> ```  
>       AAA  
>       ===  
>       BBB  
>       ---  
>   ```

AAA
===
BBB
---

>   ```
>       # 这是一级标题
>       ## 这是二级标题
>       ### 这是三级标题
>       #### 这是四级标题
>   ```

# 这是一级标题
## 这是二级标题
### 这是三级标题
#### 这是四级标题

# 列表 

> ```  
> - AAA  
>     + aaa  
>     + bbb  
>     + ccc  
> - BBB  
> - CCC  
>  
> * XXX  
> * YYY  
> * ZZZ  
>  
> * CCC  
>  
> * DDD  
> * EEE  
>  
> 1. ABC  
> 2. BCD  
> 3. CED  
> ```

- AAA
    + aaa
    + bbb
    + ccc
- BBB
- CCC

* XXX
* YYY
* ZZZ

* CCC

* DDD
* EEE

1. ABC
2. BCD
3. CED

# 引用
> ```  
> > ASP.NET Core is a signiﬁcant redesign of ASP.NET.  
>  
> >   aaaaa  
>     bbbbb  
>  
> >   ccccc  
> >   ddddd
>  
> eee
> ```


> ASP.NET Core is a signiﬁcant redesign of ASP.NET.

>   aaaaa
    bbbbb

>   ccccc
>   ddddd

eee


> ```  
> * AAA  
>  
>     HI  
>     >   ABC        
>         ABCDEF  
>  
>     > 123  
>  
>     789  
>     > 456  
> * BBB  
>  
>     HELLO  
> ```

* AAA

    HI
    >   ABC        
        ABCDEF

    > 123

    789
    > 456
* BBB

    HELLO

# 代码区块
> 要在 Markdown 中建立代码区块很简单，只要简单地缩进 4 个空格或是 1 个制表符就可以了

> ```  
> C# code below:  
>  
>     public void Hello()  
>     {  
>         Console.WriteLine("HelloWorld");  
>     }  
>  
> JavaScript code Below:  
>  
>     function hello(){  
>         console.log('Hello JavaScript');  
>     }  
>  
> HTML code Below:  
>  
> >       <!DOCTYPE HTML>  
> >       <html>  
> >           <head>  
> >               <meta charset="utf-8"/>  
> >               <title>h5 template</title>  
> >           </head>  
> >           <body>  
> >           </body>  
> >       </html>  
> ```

C# code below:

    public void Hello()
    {
        Console.WriteLine("HelloWorld");
    }

JavaScript code Below:

    function hello(){
        console.log('Hello JavaScript');
    }

HTML code Below:

>       <!DOCTYPE HTML>
>       <html>
>           <head>
>               <meta charset="utf-8"/>
>               <title>h5 template</title>
>           </head>
>           <body>
>           </body>
>       </html>

# 分隔线
> 你可以在一行中用三个以上的星号、底线来建立一个分隔线，行内不能有其他东西。你也可以在星号或是减号中间插入空格

> ```  
> ***  
> aaa  
> _ _ _  
> > bbb  
> * * *  
> ccc  
> ```

***
aaa
_ _ _
> bbb
* * *
ccc

# 链接
> Markdown 支持两种形式的链接语法：行内式 和 参考式 两种形式  
> 要建立一个 行内式 的链接，只要在方块括号后面紧接着圆括号并插入网址链接即可，如果你还想要加上链接的 title 文字，只要在网址后面，用双引号把 title 文字包起来即可  
> 参考式 的链接是在链接文字的括号后面再接上另一个方括号，而在第二个方括号里面要填入用以辨识链接的标记,接着，在文件的任意处，你可以把这个标记的链接内容定义出来  

Example0:

> ```  
> [demo1](demo1.md "baidu1")  
> ```

[demo1](demo1.md "baidu1")

Example1:

> ```  
> [Baidu](http://baidu.com "baidu1")  
> ```

[Baidu](http://baidu.com "baidu1")

Example2:

> ```  
> I get 10 times more traffic from [Google][1] than from [Yahoo][2] or [Bing][3].  
>  
> [1]: http://google.com.hk/ "Google"  
> [2]: http://search.yahoo.com/ "Yahoo Search"   
> [3]: http://global.bing.com/ "Bing Search"  
> ```

I get 10 times more traffic from [Google][1] than from [Yahoo][2] or [Bing][3].  

[1]: http://google.com.hk/ "Google"  
[2]: http://search.yahoo.com/ "Yahoo Search"   
[3]: http://global.bing.com/ "Bing Search"

Example3:

> ```  
> I get 10 times more traffic from [Google][] than from [Yahoo][] or [bing][].  
>  
> [google]: http://google.com/ "Google"  
> [yahoo]: http://search.yahoo.com/ "Yahoo Search"  
> [bing]: http://cn.bing.com/ "Bing Search"  
> ```

I get 10 times more traffic from [Google][] than from [Yahoo][] or [bing][].

[google]: http://google.com/ "Google" 
[yahoo]: http://search.yahoo.com/ "Yahoo Search" 
[bing]: http://cn.bing.com/ "Bing Search"

# 图片
> Markdown 使用一种和链接很相似的语法来标记图片，同样也允许两种样式：行内式 和 参考式  
>   行内式的图片语法看起来像是：
>  
>       ![Alt text](/path/to/img.jpg)
>       ![Alt text](/path/to/img.jpg "Optional title")
>   一个惊叹号 ! ,接着一个方括号，里面放上图片的替代文字,接着一个普通括号，里面放上图片的地址，最后还可以用引号包住并加上 选择性 的 'title' 文字  
>   参考式的图片语法则长得像这样：
>
>       ![Alt text][id]
>   id是图片参考的名称，图片参考的定义方式则和链接参考一样

#### logo of Baidu and Google  
pic example1:  

> ```  
> ![Baidu](pics/bd_logo1.png)  
> ![Google](pics/googlelogo.png)  
> ```  

![Baidu](pics/bd_logo1.png)  
![Google](pics/googlelogo.png)  

pic example2:  
> ```  
> ![BaiduLogo][]  
> ![GoogleLogo][]  
>  
> [BaiduLogo]: pics/bd_logo1.png "Baidu"  
> [GoogleLogo]: pics/googlelogo.png "Google"  
> ```

![BaiduLogo][] 
![GoogleLogo][]  

[BaiduLogo]: pics/bd_logo1.png "Baidu"
[GoogleLogo]: pics/googlelogo.png "Google"

# 其他
## 自动链接
> Markdown 支持以比较简短的自动链接形式来处理网址和电子邮件信箱，只要是用尖括号 包起来， Markdown 就会自动把它转成链接。一般网址的链接文字就和链接地址一样  
> 邮址的自动链接也很类似，只是 Markdown 会先做一个编码转换的过程，把文字字符转成 16 进位码的 HTML 实体，这样的格式可以糊弄一些不好的邮址收集机器人  

> ```  
> <http://cn.bing.com>   
> <ben121011@126.com>  
> ```  

<http://cn.bing.com>   
<ben121011@126.com>  

## 妙用反斜杠
> Markdown 可以利用反斜杠来插入一些在语法中有其它意义的符号，例如：如果你想要用 星号加在文字旁边的方式来做出强调效果（但不用 \<em> 标签），你可以在星号的前面加 上反斜杠  

> ```  
> \*literal asterisks\*  
> \**literal asterisks\**  
> ```

\*literal asterisks\*  
\**literal asterisks\**

> Markdown 支持以下这些符号前面加上反斜杠来帮助插入普通的符号：  
>
>       \ 反斜线 
>       ` 反引号
>       * 星号 
>       _ 底线
>       {} 花括号
>       [] 方括号 
>       () 括弧 
>       # 井字号 
>       + 加号 
>       - 减号 
>       . 英文句点 
>       ! 惊叹号
