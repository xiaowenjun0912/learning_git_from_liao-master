
我

![git 关联.png](http://upload-images.jianshu.io/upload_images/4712888-7703bd9ced32324f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
接下来，我们先进入 刚刚创建的 git 仓库，在 .git 同级目录下，创建一个 .gitignore 文件，我的文件内容如下：
```java

# Created by https://www.gitignore.io/api/eclipse
### Eclipse ###
target/
testLogs/
.metadata
bin/
tmp/
*.tmp
*.bak
*.swp
*~.nib
local.properties
.settings/
.loadpath
.recommenders
# External tool builders
.externalToolBuilders/
# Locally stored "Eclipse launch configurations"
*.launch
# PyDev specific (Python IDE for Eclipse)
*.pydevproject
# CDT-specific (C/C++ Development Tooling)
.cproject
# Java annotation processor (APT)
.factorypath
# PDT-specific (PHP Development Tools)
.buildpath
# sbteclipse plugin
.target
# Tern plugin
.tern-project
# TeXlipse plugin
.texlipse
# STS (Spring Tool Suite)
.springBeans
# Code Recommenders
.recommenders/
# Scala IDE specific (Scala & Java development for Eclipse)
.cache-main
.scala_dependencies
.worksheet
### Eclipse Patch ###
# Eclipse Core		
.project
# JDT-specific (Eclipse Java Development Tools)		
.classpath
# End of https://www.gitignore.io/api/eclipse
```
这样就可以排除我们不想被 git 管理的文件，放心提交了。
接下来回到 STS 在项目上右键选择 Team，git 的常规操作菜单都在这里，和命令行操作一样，add 后 commit ，这时就一切 OK 了，如图：

![提交完成.png](http://upload-images.jianshu.io/upload_images/4712888-0e144e6f45472759.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
- push 到 github

![图片.png](http://upload-images.jianshu.io/upload_images/4712888-9f944b5e7d90683a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

直接在 URI 中填入 github 仓库地址，其它项目会自动补充，然后下一步即可。