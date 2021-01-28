---
layout: post
title:  "dll/lib的生成与使用"
header-style: text
date:   2018-01-24 22:46:01
categories: 动动手
tags: 动手
---
* content
{:toc}

---
## **具体操作**：[步骤如下](https://github.com/7huang/UtilityRoom/blob/master/lib-dll-create-and-using.docx)

### dll 文件生成（vs 环境）：
1.创建动态库工程，获取.dll 和.lib
2.使用.dll ： 将.dll/.lib 分别添加到项目的debug目录和项目属性->连接器下的附加库目录。
3.调用动态库：
	#pragma  comment(lib ,"Tdll.lib")
    
### lib 文件生成（vs 环境）
1.创建静态库工程获取.lib。 创建封装好的（.h/ /cpp）文件。编译即可以在debug目录下获取
2.使用：所在项目配置：项目属性->连接器下的附加库目录，添加动态库文件所在文件路径。同时需要包含相应头文件。
#pragma  comment(lib ,"Testlib.lib")
    