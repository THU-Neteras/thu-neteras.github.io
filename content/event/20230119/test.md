@[toc](10分钟无痛入门markdown，只需学8个核心用法)

> 如果看完不会，欢迎拿刀砍我！！！
## 为啥写这篇博客？
----
众所周知，纯文本的markdown语言有**跨平台、简洁易用、所写即所得、排版美观、版本管理**等特点，极大简化了富文本排版，几乎成为程序员写作输出的必学语言。

## 8个核心用法
----

**1、目录生成**：用于文章正文前，一键生成目录，前提是后文必须以`##`等做层级标题管理
- 指令：`[toc]`
- 补充：CSDN博客可修改为`@[toc](文章标题xxx)`，能顺带有文章标题。

**6、代码块**
```c
一句话中标识代码，初始化`int a = 0`, 即可。

段落代码，使用如下：
  // ```后面可以写c/cpp/python/java等，用于对应语言渲染
int a = 0;
int b = a;
// 正式使用时，应去掉左右两个*，以便跟前面```配对
```
**7、超链接**：用于跳转到其他网页
- 指令：`[网址名称](具体网址)`
- 示例：`[来知晓CSDN博客](https://blog.csdn.net/qq_17256689)`
- 效果：[来知晓CSDN博客](https://blog.csdn.net/qq_17256689)

**8、附图**：用于富文本的图片展示，与超链接指令只差个感叹号
- 指令：`![]()`
- 示例：`![一张松山湖的照片](https://img-blog.csdnimg.cn/1ab9c654a930490292e76731864f1cb3.jpg)`

本文排版全部只用到以上所提**8个核心用法**，看到这儿，你是否已经10分钟无痛入门markdown了呢？读者如有兴趣，可自行阅读以下参考，扩展你所需的知识。
1. [markdown语言创始人JOHN GRUBER写的介绍](https://daringfireball.net/projects/markdown/)
2. [腾讯云：Markdown 语法手册 （完整整理版）](https://cloud.tencent.com/developer/article/1024105)
3. [少数派：Markdown 完全入门](https://sspai.com/post/36610)