# BaiduYunDownload
本项目目前提供个人网盘文件的解析下载(单文件)及分享链接的解析下载(单文件/文件夹)
## 个人网盘文件
格式：
> /我的资源/1.mp4     #从根目录写起
## 分享链接（文件夹）
格式：
> /   #表示下载整个文件夹<br>
> /文件夹名/文件(夹)名   

##注意事项
需要创建本地临时文件夹并在settings.py文件中添加该临时文件夹目录
需要在settings.py文件中添加下载目录
欢迎各位大佬评论，目前在Windows系统下测试通过
若为其他系统，验证码图片打开可能有问题，自行修改parse_main.py中的图片打开命令
