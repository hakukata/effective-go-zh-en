《Effective Go》中英双语版
===

> 本开源书 forked from [《Effective Go》中英双语版](https://github.com/bingohuang/effective-go-zh-en)，作者为 [bingohuang](https://github.com/bingohuang)，欢迎大家 star 原作者的 [repo](https://github.com/bingohuang/effective-go-zh-en)，以便获得最新更新，谢谢！

## *Effective Go* - 《实效 GO 编程》

### Introduction

Go is a new language. Although it borrows ideas from existing languages, it has unusual properties that make effective Go programs different in character from programs written in its relatives. A straightforward translation of a C++ or Java program into Go is unlikely to produce a satisfactory result—Java programs are written in Java, not Go. On the other hand, thinking about the problem from a Go perspective could produce a successful but quite different program. In other words, to write Go well, it's important to understand its properties and idioms. It's also important to know the established conventions for programming in Go, such as naming, formatting, program construction, and so on, so that programs you write will be easy for other Go programmers to understand.

This document gives tips for writing clear, idiomatic Go code. It augments the [language specification](https://go-zh.org/ref/spec), [the Tour of Go](https://tour.golang.org/), and [How to Write Go Code](https://go-zh.org/doc/code.html), all of which you should read first.

### 引言

Go 是一门全新的语言。尽管它从既有的语言中借鉴了许多理念，但其与众不同的特性，使得用 Go 编程在本质上就不同于其它语言。将现有的 C++ 或 Java 程序直译为 Go 程序并不能令人满意——毕竟 Java 程序是用 Java 编写的，而不是 Go。 另一方面，若从 Go 的角度去分析问题，你就能编写出同样可行但大不相同的程序。 换句话说，要想将 Go 程序写得好，就必须理解其特性和风格。了解命名、格式化、程序结构等既定规则也同样重要，这样你编写的程序才能更容易被其他程序员所理解。

本文档就如何编写清晰、地道的 Go 代码提供了一些技巧。它是对 [语言规范](https://go-zh.org/ref/spec)、 [Go 语言之旅](https://tour.golang.org/) 以及 [如何使用 Go 编程](https://go-zh.org/doc/code.html) 的补充说明，因此我们建议您先阅读这些文档。

---

`Effective Go` 作为 `GO` 语言的入门必读教程，值得每位初学者好好阅读一遍，编辑成书，方便阅读交流。

---
## 当前完成章节（全部完成）：

1. [前言](README.md)
2. [引言](01_Overview.md)
3. [格式化](02_Formatting.md)
4. [注释](03_Commentary.md)
5. [命名](04_Names.md)
6. [分号](05_Semicolons.md)
7. [控制结构](06_Control_structures.md)
8. [函数](07_Functions.md)
9. [数据](08_Data.md)
10. [初始化](09_Initialization.md)
11. [方法](10_Methods.md)
12. [接口和其他类型](11_Interfaces_and_other_types.md)
13. [空白标识符](12_The_blank_identifier.md)
14. [内嵌](13_Embedding.md)
15. [并发](14_Concurrency.md)
16. [错误](15_Errors.md)
17. [一个 Web 服务器](16_A_web_server.md)


> 改版说明：@2016.8.6 by bingoHuang, revision to Chinese & English version.

> 李笑来在他的新书 [《人人都是工程师》](http://xiaolai.li/2016/06/12/makecs-preface/) 中说过一句话： 在中国，对绝大多数人来说，**`English + Computer Skills = Freedom`（英语 + 计算机技能 = 自由）**

> 我非常的赞同。英语和计算机技能是相辅相成，学习好一门编程语言（如 `Go`）的同时，还能加强英语学习，何乐而不为。所以我决定将本书改版成中英双语版，方便更多的人来学习阅读。

> 特别感谢 [Golang](https://golang.org) 官网提供的英文版教程。

> 感谢 [hellogcc](http://www.hellogcc.org) 提供的 [中文翻译版一](http://www.hellogcc.org/effective_go.html)，这是我之前制作中文版电子书所参考的资料，翻译的很用心。

> 要更感谢 [Go 语言中文社区](https://go-zh.org/) 提供的 [中文翻译版二](https://go-zh.org/doc/effective_go.htm)，此翻译更贴切有味道，不可多得。本人已和 [Go-zh 项目组](https://github.com/Go-zh/go) 沟通过，获取了该社区的授权，故将此作为双语版的中文版本。

### 参考

*参考官方英文版：[Effective Go 英文版](https://golang.org/doc/effective_go.html)*

~~*参考中文翻译版一：[Effective Go 中文版](http://www.hellogcc.org/effective_go.html)*~~

*参考中文翻译版二：[Effective Go 中文版](https://go-zh.org/doc/effective_go.htm)*

### Read, Fork and Star

+ **[Read on Gitbook](https://www.gitbook.com/book/bingohuang/effective-go-zh-en/details)**

+ **[Fork on GitHub](https://github.com/bingoHuang/effective-go-zh-en)**

+ 请顺手点一下 `STAR` ，或者留言讨论，这是对我最大的鼓励！

### 下载

为了让大家更方便阅读，在此提供 [网易蜂巢对象存储](https://c.163.com/dashboard#/m/nos/) 的下载地址：

- [x] [PDF格式](http://bingohuang.nos-eastchina1.126.net/effective-go-zh-en-gitbook.pdf)
- [x] [EPUB格式](http://bingohuang.nos-eastchina1.126.net/effective-go-zh-en-gitbook.epub)

## License
除特别注明外， 本页内容均采用知识共享 - 署名（CC-BY）3.0 协议授权，代码采用 [BSD 协议](LICENSE) 授权。
