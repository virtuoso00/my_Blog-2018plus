# 通过MkDocs搭建个人博客

> 9分钟拥有一个自己的博客
>
> date: 2018-05-19

---

搭建和维护个人博客以及写博客是一件非常酷的事情，这也是每个程序员生活的一部分。一个个人博客既是自己的一张名片也是自己学习的见证。

搭建和托管博客的方法有很多，很久以前我曾经推荐过通过GitHub托管Jekyll项目，并通过GitHub Pages服务展示博客的方法。

> 详见，[在GitHub上通过Jekyll搭建个人博客](../sssta/2017-10-08-SSSTA-Blog.md)

Jekyll是一个强大的静态网站生成器，结合GitHub Pages的完美支持，非常便于你展示你的想法。但是，他并不易于操作，如果没有前端的知识你甚至没法操作，你只能被动接受Jekyll主题设计者在设计中加入的一大堆垃圾。

如果你只是想好好地写写文章，并让他们优雅地展示出来，那用Jekyll肯定是不合适的，或者至少是不方便的。很快我将为你介绍一个更优雅的方式应该具备的特性。

## MkDocs概述

> MkDocs is a fast, simple and downright gorgeous static site generator that's geared towards building project documentation.
>
> MkDocs是一个致力于构建项目文档的快速、简单和绝对优雅的静态网站生成器。

MkDocs是被设计用于构建文档的，所以它特别适于注重内容的静态站点，它至少有以下优雅之处

- 清晰的文章分级目录
- 文章内标题导航
- 全站文本搜索
- 全部Python Markdown扩展
- 优雅、易于阅读的Markdown渲染

除此之外，MkDocs的多数主题都没有多余的内容，只专注于展示文章，正如[该站点](https://blog.keybrl.ink)所呈现的。而且，你需要做的也只是写文章，其他细节都能很便捷地设置。这比Jekyll还简单，而且更优雅。  
**酷炸了不是吗？**

接下来我将分部分逐步介绍通过MkDocs构建、部署个人博客的过程。点击列表中的超链接可以直接跳转到相应章节。

1. [环境搭建和MkDocs的安装](#_1)
2. [构建一个最简单的网站](#_2)
3. [通过Markdown写自己的文章](#_3)
4. [选择主题](#_4)
5. [完善配置文件](#_5)
6. [站点托管与部署](#_6)

!!! Tip "阅读提示"
    本篇旨在从一个大的视角了解通过MkDocs构建站点的过程，而不是作为指导工作的手册、文档

    对于上述的部分内容，本篇可能只会作简要描述，并引导读者前去阅读[MkDocs的官方文档](http://www.mkdocs.org/)或另一篇更详尽的文章

    [本文最后]()有一个列表，列出了全部在本文出现的建议阅读的相关的官方文档和其它文章，它们对于读者建立完善、准确的认识将更有帮助。

## 准备工作

MkDocs 是一个以 Python 实现的轻量化静态网站生成器

所以，首先我们需要安装 Python ，在 Debian/Ubuntu 下只需要通过 apt 安装即可

```bash
apt install python
```

!!! Warning "兼容的Python版本"
    > 官方文档的说明是：MkDocs supports Python versions 2.7, 3.3, 3.4, 3.5 and pypy.

    但事实上我用 Python 3.6 也没有任何问题，所以我建议首先尝试 Python 的最新稳定版，如果存在兼容问题再参考官方推荐

安装Python的第三方包管理器 pip

```bash
apt install python-pip
```

在Windows环境下安装 Python 和 pip 请参考 [python.org](https://www.python.org)

然后通过 pip 安装 MkDocs

```bash
pip install mkdocs
```

检查安装情况

```bash
pip show mkdocs
```

如果有出现对 MkDocs 的简要描述即安装成功

!!! Tip "强烈推荐WSL"
    在 Windows 环境下进行与 Web 相关的开发经常都很不方便，如果既不喜欢虚拟机，又不习惯长时间在 Linux 下工作，又不想来回切换系统，那你一定要试试 WSL

    > WSL: Windows Subsystem for Linux

    WSL 是 Windows 的 Linux 子系统，可以在 Windows 中运行 Linux 应用，它只能通过命令行进行交互，有兴趣自行 Google

## 好的开端

MkDocs 给我们提供了一种简单的创建 MkDocs 项目的方式

```bash
mkdocs new hhhh
```

## 跃动的思想

## 颜值即正义

## 尽在掌控

## 锋芒毕露

---

未完成...
