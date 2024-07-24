# 图片

## 一、说明

其他仓库需要显示图片时所需要进行的操作

## 二、

需要上传到本仓库的图片提交代码：(复制粘贴到`Git Bash`命令行)

在项目所在的文件夹中新建images，然后在项目所在文件夹中发送以下命令，第一次上传时：

```bash
git init
git add images/	
git commit -m "增加图片"
git branch -M main
git remote add origin git@github.com:Handoly/仓库名.git
git push -u origin main
```

后续需要上传时：

```
git add images/	
git commit -m "增加图片"
git branch -M main
git push -u origin main
```

若是本README.md文件需要更新时，使用下面代码：

```
git init
git add README.md
git commit -m "修改内容"
git branch -M main
git remote add origin git@github.com:Handoly/images.git
git push -u origin main
```

