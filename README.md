# Github图床建立 

![Static Badge](https://img.shields.io/badge/%E9%80%8D%E9%81%A5-Happy-rgb(201%2C%2091%2C%200)) `Github` `图床`

## 1. 前言

很久了才想起我有个博客，本来准备在博客上写点东西，才发现没有图床索性就马上建立一个Github图床。看教程的时候发现了github徽章教程，就是上面这个东西。这个先不在这里说，可能会另开一篇吧。

## 2. 准备工作

只需要一个GitHub账号，如果没有，自行注册就不在这里赘诉了

![github](https://cdn.jsdelivr.net/gh/H-Bole/Picture-home/Halo/Creat_picture_home/github.png)

## 3. 正式搭建

### 3.1 创建仓库

登录你的 Github 后，创建一个新的仓库。

![创建入口](https://cdn.jsdelivr.net/gh/H-Bole/Picture-home/Halo/Creat_picture_home/%E5%88%9B%E5%BB%BA%E5%85%A5%E5%8F%A3.png)

### 3.2 填写仓库资料

填写仓库相关资料，一般只需要选一个合适的仓库名，然后确保仓库为 public 其他的保持默认就好。

![建立仓库](https://cdn.jsdelivr.net/gh/H-Bole/Picture-home/Halo/Creat_picture_home/%E5%88%9B%E5%BB%BA%E5%AD%98%E5%82%A8%E5%BA%93.png)

### 3.3 完成创建

一般创建成功后，会出现如下界面，至此，我们的图床算是创建好了，接下来就是如何上传图片了。

![创建完成](https://cdn.jsdelivr.net/gh/H-Bole/Picture-home/Halo/Creat_picture_home/%E5%88%9B%E5%BB%BA%E5%AE%8C%E6%88%90.png)

## 4. 上传图片

通过上述步骤，我们的图床已经搭建好了，接下来介绍如何使用 PicGo 进行图片上传。

1. 去官网安装 PicGo，然后打开软件。
![picgo](https://cdn.jsdelivr.net/gh/H-Bole/Picture-home/Halo/Creat_picture_home/picgo.png)

2. 配置 PicGo，首先去 Github 创建一个 token。
   - 依次打开 Settings -> Developer settings -> Personal access tokens，然后点击 generate new token。
![设置入口](https://cdn.jsdelivr.net/gh/H-Bole/Picture-home/Halo/Creat_picture_home/%E8%AE%BE%E7%BD%AE%E5%85%A5%E5%8F%A3.png)
   - 填写及勾选相关信息，然后点击 Generate token。
   - 复制生成的 token 到备忘录中备用。

3. 配置 PicGo。
   - 打开 图床设置 -> Github 图床。
   - 填写相关信息，点击确定。如果要将其作为默认图床的话，点击设为默认图床。

4. 上传图片。
   - 通过上传区上传即可，也可以使用快捷键上传（默认上传键为 Ctrl + Shift + P）。

![结束](https://pic4.zhimg.com/80/v2-5222e928875aff8540ff7824a0d6a827_1440w.webp "ways")

## 5. 加速访问

有时候我们上传到 Github 的图片访问太慢了，甚至加载不出来，这时可以使用 jsDelivr 进行免费加速。  只需在 PicGo 图床配置中添加如下自定义域名即可：
    
```https://cdn.jsdelivr.net/gh/用户名/仓库名```

```比如我的就是 https://cdn.jsdelivr.net/gh/H-Bole/Picture-home```
