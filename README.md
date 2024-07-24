# 图片

## 一、说明

存放一些在其他仓库需要显示的图片

## 二、

需要上传到本仓库的图片提交代码：(复制粘贴到`Git Bash`命令行)

在图片所在的文件夹中，第一次上传时：

```bash
git init
git add .	
git commit -m "增加图片"
git branch -M main
git remote add origin git@github.com:Handoly/images.git
git push -u origin main
```

后续需要上传时：

```
git add .	
git commit -m "增加图片"
git branch -M main
git push -u origin main
```

