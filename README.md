# Github图床建立 
![Static Badge](https://img.shields.io/badge/%E9%80%8D%E9%81%A5-Happy-rgb(201%2C%2091%2C%200))  `Github`      `图床`
#
## 1.前言

    
        很久了才想起我有个博客，本来准备准备在博客上写点东西，才发现没有图床索性就马上建立一个Github图床（看教程的时候发现了github徽章教程，就是上面这个东西。这个先不在这里说，可能会另开一篇吧）

## 2.准备工作
    只需要一个GitHub账号，如果没有，自行注册就不在这里赘诉了
![github](https://cdn.jsdelivr.net/gh/H-Bole/Picture-home/Halo/Creat_picture_home/github.png)
## 3.正式搭建
    3.1登录你的 Github 之后，创建一个新的仓库；
![创建入口](https://cdn.jsdelivr.net/gh/H-Bole/Picture-home/Halo/Creat_picture_home/%E5%88%9B%E5%BB%BA%E5%85%A5%E5%8F%A3.png)

    3.2填写仓库先关资料，一般只需要选一个合适的仓库名，然后确保仓库为 public 其他的保持默认就好；
![建立仓库](https://cdn.jsdelivr.net/gh/H-Bole/Picture-home/Halo/Creat_picture_home/%E5%88%9B%E5%BB%BA%E5%AD%98%E5%82%A8%E5%BA%93.png)

    3.3一般创建成功之后，会出现如下界面，至此，我们的图床算是创建好了，接下来就是如何上传图片了；
![创建完成](https://cdn.jsdelivr.net/gh/H-Bole/Picture-home/Halo/Creat_picture_home/%E5%88%9B%E5%BB%BA%E5%AE%8C%E6%88%90.png)

## 4. 上传图片
    通过上面的步骤，我们的图床时搭建好了，但是通过传统的方法向 Github 上传图片太麻烦了，这里我们推荐使用一个开源图床工具 PicGo 来作为我们的图片上传工具；

    去官网安装PicGo，我们主要讲讲如何用它来上传图片。安装后，打开软件其主页面如下：
![picgo](https://cdn.jsdelivr.net/gh/H-Bole/Picture-home/Halo/Creat_picture_home/picgo.png)

    接下来就是配置 PicGo 的过程了。

    首先，我们先要去 Github 创建一个 token；
    依次打开 Settings -> Developer settings -> Personal access tokens，最后点击 generate new token；
![设置入口](https://cdn.jsdelivr.net/gh/H-Bole/Picture-home/Halo/Creat_picture_home/%E8%AE%BE%E7%BD%AE%E5%85%A5%E5%8F%A3.png)

![token第二步](https://cdn.jsdelivr.net/gh/H-Bole/Picture-home/Halo/Creat_picture_home/token%E7%AC%AC%E4%BA%8C%E6%AD%A5.png)
![第三步](https://cdn.jsdelivr.net/gh/H-Bole/Picture-home/Halo/Creat_picture_home/token%E7%AC%AC%E4%B8%89%E6%AD%A5.png)

    填写及勾选相关信息，然后点击 Genetate token 即可；
![第四步](https://cdn.jsdelivr.net/gh/H-Bole/Picture-home/Halo/Creat_picture_home/token%E7%AC%AC%E5%9B%9B%E6%AD%A5.png)
![第五步](https://cdn.jsdelivr.net/gh/H-Bole/Picture-home/Halo/Creat_picture_home/%E7%82%B9%E5%87%BB%E7%94%9F%E6%88%90.png)
    token 生成好以后，注意它只会显示一次，所以你最好把它复制下来到你的备忘录存好，方便下次使用，否则下次有需要重新新建；
![生成成功](https://cdn.jsdelivr.net/gh/H-Bole/Picture-home/Halo/Creat_picture_home/token%E7%94%9F%E6%88%90.png)
    
    配置 PicGo，依次打开 图床设置 -> Github 图床；
![配置](https://cdn.jsdelivr.net/gh/H-Bole/Picture-home/Halo/Creat_picture_home/%E9%80%89%E6%8B%A9%E5%9B%BE%E5%BA%8A.png)

    填写相关信息，最后点击 确定即可，要将其作为默认图床的话，点击设为默认图床；
![填写信息](https://cdn.jsdelivr.net/gh/H-Bole/Picture-home/Halo/Creat_picture_home/%E9%85%8D%E7%BD%AE%E4%BF%A1%E6%81%AF.png)

    上传图片，通过上传区上传即可（Ctrl V 或者将图片拖拽都可以），也可以通过快捷键的方式上传（默认上传键为 Ctrl + Shift + P）；
![结束](https://pic4.zhimg.com/80/v2-5222e928875aff8540ff7824a0d6a827_1440w.webp "ways")
## 5. 加速访问
    大家可能会发现，我们上传到 Github 的图片有时候访问太慢了，有时候甚至直接加载不出来！

    这时候我们就可以用 jsDelivr 进行免费加速，而设置的方法也很简单，只需要在我们 PicGo 图床配置中添加如下自定义域名即可；
    https://cdn.jsdelivr.net/gh/用户名/仓库名
    比如我的就是 https://cdn.jsdelivr.net/gh/H-Bole/Picture-home


