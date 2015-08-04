# EasyFonts
----
#如何使用EasyFonts（How to use EasyFonts）

> 这个项目主要是为了告诉大家如何在项目中引用EasyFonts，并且运行EasyFonts的示例。
> This project wants to tell you how to use EasyFonts in your project, and help you to run the example.

开源项目地址：[https://github.com/vsvankhede/easyfonts](https://github.com/vsvankhede/easyfonts "https://github.com/vsvankhede/easyfonts")  
Project Addreess: [https://github.com/vsvankhede/easyfonts](https://github.com/vsvankhede/easyfonts "https://github.com/vsvankhede/easyfonts")

#### 为什么写这篇文章 (why)
无意间看到了**EasyFonts**，发现这个项目非常不错，能够快速帮助大家在项目中使用各种炫酷的字体。但是该项目下载后，我想看看效果，但是结果令我无比蛋疼，项目混杂错乱。当然，也许我使用的`Eclipse`的原因，没有gradle，不是Android Studio，包括很多其他的项目，都可能存在这个问题：没有考虑eclipse用户的感受。那么，怪我咯？！国内还是有很多同学使用Eclipse滴，所以，如果你已经知道这么的文字是否值得你看下去了。

sorry, guys! I cannot zhuangbility to write more, as you see, my English is to poor to surport me to write more. What I want to say is this article is going to help you run **EasyFonts** in **Eclipse**, if it is useless, plz forgive me.

#### 开始使用 (how)

- 导入**EasyFonts_library**  
  原作者提供了一个library方便大家调用，因此将下载的包解压缩之后，有个`EasyFonts_library`目录，这个就是library包了。  

    > 需要注意的是，这个library需要引用**android-support-v7-appcompat**包。什么？没有这个包？看看`android-support-v7-appcompat`这个文件夹吧。
  
  1. 导入`android-support-v7-appcompat`和`EasyFonts_library`到工作空间。

  2. 右键`android-support-v7-appcompat`，选择左侧`Android`选项，勾选右侧下方的 `Is Library`，然后`Apply`，然后 `OK`。

  3. 右键`EasyFonts_library`，选择左侧`Android`选项，勾选右侧下方的 `Is Library`，同时，点击`Add…`，选中上面的`android-support-v7-appcompat`，然后`Apply`，然后 `OK`。
  
  EasyFonts_library 导入完成
  
- 导入示例**EasyFontsExample**  
  导入后，添加`EasyFonts_library`为library即可。
  

  接着运行`EasyFontsExample`就可以看到效果了。
  
  如果大家在自己的工程中想使用它，请参考`EasyFontsExample`，添加library即可。
  > 需要注意的是，如果你的项目直接引用过V7包，可能会存在冲突，取消项目直接引用V7包即可


如果有问题可以提出来。