1.安装git
  > apt-get install git

2.设置git
  >git config  --global user.name "Your Name"

  >git config --global user.email "email@xample.com"

3.创建版本库
  >git init

4.提交到库

>git add file
>git commit -m "本次提交说明"

5.查看仓库状态

>git status

6.status查看仓库有何不同
>git diff filename

7.查看版本
>git log

8.退回版本
>git reset --hard 652456 (版本号)

9.后悔退回（回到未来）
>git reflog

>git reset --hard 版本号

10.工作区与暂存区

![image](http://upload-images.jianshu.io/upload_images/74242-82b43e27d5fff326?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
