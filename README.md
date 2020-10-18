# blogpics
pictures on my blog 

# picture with cdn sample
创建一个 GitHub 仓库作为图床仓库，上传提交图片到仓库中
在要使用 GitHub 图床图片的地方将链接换为 https://cdn.jsdelivr.net/gh/{user}/{repo}/图片路径
举个栗子，比如 GitHub 官方仓库 github/explore 下话题 GitHub 图片原始路径是：https://github.com/github/explore/blob/master/topics/github/github.png 访问起来贼慢。

使用 jsDelivr 加速后的地址：https://cdn.jsdelivr.net/gh/github/explore/topics/github/github.png 访问速度飞起，享受 jsDelivr 提供的全球 CDN 加速。

jsDelivr 还支持加载指定文件版本和自动压缩 JS，具体用法可以参考[官方教程](https://www.jsdelivr.com/features#gh)。


如果觉得手动上传 GitHub 图床仓库太麻烦，那就使用这款图床神器吧 https://github.com/Molunerfinn/PicGo

本方法来源于 https://ld246.com/article/1583894928771
