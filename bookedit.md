# 图书编辑

> gitbook书籍编辑有两种方法：
>
> - [下载](https://github.com/GitbookIO/editor/releases)使用[gitbook editor](https://github.com/GitbookIO/editor/releases) ，[gitbook editor](https://github.com/GitbookIO/editor/releases) 实际上就是一个本地应用版的在线编辑器，使用方式和 [gitbook](https://yuzeshan.gitbooks.io/gitbook-studying/content/book/gitbook.com)在线编辑器类似，由于使用比较简单，本书不作介绍；
>
> - gitbook命令行&markdown编辑：`README.md`和`SUMMARY.md`是Gitbook项目必备的两个文件，也就是一本最简单的gitbook也必须含有这两个文件，它们在一本Gitbook中具有不同的用处.

**gitbook常用命令预览**

```
gitbook init //初始化目录文件
gitbook help //列出gitbook所有的命令
gitbook –help //输出gitbook-cli的帮助信息
gitbook build //生成静态网页
gitbook serve //生成静态网页并运行服务器
gitbook build –gitbook=2.0.1 //生成时指定gitbook的版本, 本地没有会先下载
gitbook ls //列出本地所有的gitbook版本
gitbook ls-remote //列出远程可用的gitbook版本
gitbook fetch 标签/版本号 //安装对应的gitbook版本
gitbook update //更新到gitbook的最新版本
gitbook uninstall 2.0.1 //卸载对应的gitbook版本
gitbook build –log=debug //指定log的级别
gitbook builid –debug //输出错误信息
参考：https://blog.iphpjs.com/2017/07/12/gitbook%E5%B8%B8%E7%94%A8%E5%91%BD%E4%BB%A4/
```

**生成书籍命令步骤预览**

```
1. gitbook init
	2. gitbook serve ./图书名称
	或2. gitbook build 图书目录 输出目录
```
