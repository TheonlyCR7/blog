---
title: Github入门教程
date: 2020-07-06 15:31:25
tags: 小教程
categories: 学习
---



## GitHub

### 注册一个账号

直接在首页注册即可啦

<!--more-->

<img src="https://gitee.com/liuminchao7/img/raw/master/Github%E5%85%A5%E9%97%A8%E6%95%99%E7%A8%8B/20200625215031114.png" alt="在这里插入图片描述"  />

要注意的是 第一项 username 别人是可见的 后面修改也会比较麻烦，所以起个好名字很重要



### 个人主页介绍

刚注册好的页面类似这样，只不过还没有自己的repositories(项目仓库)，stars(收藏)

<img src="https://gitee.com/liuminchao7/img/raw/master/Github%E5%85%A5%E9%97%A8%E6%95%99%E7%A8%8B/20200625215048987.png" alt="在这里插入图片描述"  />

*   Overview板块

    这里是你的主页部分

<img src="https://gitee.com/liuminchao7/img/raw/master/Github%E5%85%A5%E9%97%A8%E6%95%99%E7%A8%8B/2020062521511921.png" alt="在这里插入图片描述"  />

下拉之后，是你创建，修改，提交的一些细节记录

<img src="https://gitee.com/liuminchao7/img/raw/master/Github%E5%85%A5%E9%97%A8%E6%95%99%E7%A8%8B/2020062521513735.png" alt="在这里插入图片描述"  />

*   项目仓库板块 Repositories

    这里展示你的项目（自己创建的，fork他人的)

<img src="https://gitee.com/liuminchao7/img/raw/master/Github%E5%85%A5%E9%97%A8%E6%95%99%E7%A8%8B/20200625215147930.png" alt="在这里插入图片描述"  />
    也可以进行项目查找工作（包括对类型，语言的筛选）

​	也可以点击`New` 绿色的按钮，进行项目创建


​    

*   项目管理板块Projects

    这里你可以描述有关项目的细节，如：拉去请求，注释，议题
<img src="https://gitee.com/liuminchao7/img/raw/master/Github%E5%85%A5%E9%97%A8%E6%95%99%E7%A8%8B/20200625215227598.png" alt="在这里插入图片描述"  />
    我暂时还没用到……



*   包注册表板块Packages

    官方给的介绍是：GitHub 包注册表 是一种软件包托管服务，允许您私下或公开托管软件包，并将包用作项目中的依赖项（暂时用不上）

    <img src="Github入门教程/image-20200625203233073.png" alt="image-20200625203233073"  />

    

*   收藏板块Stars

    这里是我们收藏的项目啦

    当我们遇到好的项目，想要以后经常看的话，点击项目上方的Star即可，项目就会被收藏啦

    改版后，star 放到了头像下方

![在这里插入图片描述](F:/Typora_img/20200625215309294.png)

​    

*   两个关注板块 Followers Following

    顾名思义，就是我们关注的技术大佬，还有关注我们的粉丝啦

![在这里插入图片描述](F:/Typora_img/20200625215329169.png)



### 创建项目仓库

创建自己的项目仓库，有很多种方法，下面列举两种常用的

*   点击右上角的加号，选择 `New repository`即可

![在这里插入图片描述](F:/Typora_img/20200625215341900.png)

*   在仓库板块，直接点击`New`即可

![在这里插入图片描述](F:/Typora_img/20200625215411915.png)



#### 创建项目

点击新建后

页面如下

![在这里插入图片描述](F:/Typora_img/20200625215429931.png)

需要填的内容有：

*   仓库名称
*   描述
*   仓库是否公开
*   是否自动创建 **README.md**  (用于仓库的进一步描述，在项目目录的下方显示)



例如
![在这里插入图片描述](F:/Typora_img/20200625215511401.png)
点击 `Create rrepository` 后

自动跳转到仓库首页
![在这里插入图片描述](F:/Typora_img/20200625215552555.png)




#### 仓库页面功能介绍

这里介绍一些常用功能，足以满足初学者

![image-20200625204605115](Github入门教程/image-20200625204605115.png)



#### 为仓库新建文件和文件夹

点击 `Create File` 后

![111](F:/Typora_img/20200625215927780.png)
进行命名
![在这里插入图片描述](F:/Typora_img/20200625220000455.png)

![在这里插入图片描述](Github入门教程/20200625220028818.png)

然后点击 `Commit new file` 即可

页面自动跳转

创建完成

![image-20200625204907622](Github入门教程/image-20200625204907622.png)


创建文件夹的话，加上 / 即可， Document为文件夹名

![image-20200625204952501](Github入门教程/image-20200625204952501.png)

创建完成

![image-20200625205028157](Github入门教程/image-20200625205028157.png)



### 观摩大神的项目

点击页面上方的 **Explore**

![image-20200625205259073](Github入门教程/image-20200625205259073.png)

可以看到上面的选择栏有众多选项可以选择

![image-20200625205443439](F:/Typora_img/image-20200625205443439.png)





Github的使用暂时我只想到这些（git 以后单独出一版）

下面来集中解决一些问题



## 关于Github访问慢的问题

在国内，Github 一直存在访问慢，图片不加载  仓库代码下载极慢甚至失败的问题

现在大多数的方法就是修改本机的host文件

host文件位置

```
C:\Windows\System32\drivers\etc
```

就是利用浏览器根据url在发送请求前，先去查找本机的 host 文件  若有，直接访问对应的服务器

下面是我的host文件对于 Github 的ip地址

```
# GitHub Start 

140.82.114.3          github.com
199.232.69.194    github.global.ssl.fastly.net

192.30.253.119    gist.github.com

151.101.184.133    assets-cdn.github.com

151.101.184.133    raw.githubusercontent.com

151.101.184.133    gist.githubusercontent.com

151.101.184.133    cloud.githubusercontent.com

151.101.184.133    camo.githubusercontent.com

151.101.184.133    avatars0.githubusercontent.com

151.101.184.133    avatars1.githubusercontent.com

151.101.184.133    avatars2.githubusercontent.com

151.101.184.133    avatars3.githubusercontent.com

151.101.184.133    avatars4.githubusercontent.com

151.101.184.133    avatars5.githubusercontent.com

151.101.184.133    avatars6.githubusercontent.com

151.101.184.133    avatars7.githubusercontent.com

151.101.184.133    avatars8.githubusercontent.com

 

 # GitHub End
```

直接放到 后面即可

若是权限不够

先在其他位置创建同名文件  先将原 host 文件的内容 复制粘贴到里面

然后后面加上  上面的 ip url  解析绑定



这样  访问慢，图片不显示的问题就解决了



## 对于下载慢的问题

可以通过  国内版github  码云来解决

1.  先将github 上仓库的url 复制  注意一定要是  https  

    ![image-20200625213154920](Github入门教程/image-20200625213154920.png)

2.  点击导入仓库

![image-20200625213054992](Github入门教程/image-20200625213054992.png)

3.  在这里填入即可

    ![image-20200625213405589](Github入门教程/image-20200625213405589.png)

4.  点击导入就可，一般速度很快

    ![image-20200625213437259](Github入门教程/image-20200625213437259.png)

5.  点击下载压缩包即可

    ![image-20200625213503636](Github入门教程/image-20200625213503636.png)



当然，码云上也有很多好项目，但完全被我用成了下载工具(狗头)

[访问慢的另一种解决方案](https://github.com/sLxiaosheng/First_Repository)



### 外记
端午节，和我爸喝了点酒（5瓶），酒醒后，改了改文章
如有错误的地方，还望指正
谢谢大家！！！