Git基本操作命令：

以下是自己总结的一些简单的操作

git init (初始化仓库)

git show   提交版本号         (展示残仓库的状态)

git add (增加到暂存区)

git commit -m "信息" (提交到仓库)

git status (查看仓库状态)

git pull (将远程仓库的提交拉到本地)

git push (将本地的提交推送到远程仓库)

git remote add "别名" 仓库地址 (连接远程仓库的地址)

git remote -v (查看当前所连接的仓库的地址)

git add . (将所有文件提交到暂存区)

git commit . -m "此次修改的信息" (将所有文件提交到本地仓库)

git clone 仓库地址

git push    "仓库地址别名" master (推送到远程仓库)

## 一、 打开本地要上传的文件地址
![图片](https://uploader.shimo.im/f/XIsWuZqya1HycliK.jpg!thumbnail)

## 二、 GitHub新建项目
![图片](https://uploader.shimo.im/f/tng13MhCye92izAb.jpg!thumbnail)

![图片](https://uploader.shimo.im/f/TwwsVQeaoWQLC4ds.jpg!thumbnail)

## 三、 获取仓库地址
[https://github.com/scl1993/UpLoadFileStep](https://github.com/scl1993/UpLoadFileStep)

![图片](https://uploader.shimo.im/f/TaUhaw6bDalNcl9O.jpg!thumbnail)

## 四、 右键，直接进入本地文件路径下git命令
![图片](https://uploader.shimo.im/f/gj2St6ewCawQaVER.jpg!thumbnail)

## 五、 Git基本操作命令
### **1、**** ****git init 初始化本地仓库**
该本地路径下可能不是一个git路径，所以直接git命令操作无法识别，提示不是Git路径。所以先执行git init 初始化

### **2、**** ****git status 查看该git路径下有哪些修改文件未合入本地仓库**
文件最好使用英文，截图可看到该word文件，有修改未合入本地仓库

![图片](https://uploader.shimo.im/f/pvEqntd8aOTN63y0.jpg!thumbnail)       

### 3、 git add 要提交的文件
git add GitUploadLearing.docx

![图片](https://uploader.shimo.im/f/lF2hxml5j3Lcsysm.jpg!thumbnail)

### 4、 git commit -m “”
git commit -m "GitLearning"

![图片](https://uploader.shimo.im/f/OdW0eUUlG94ekJZQ.jpg!thumbnail)

### 5、 git remote -v 查看当前仓库链地址
截图所示，没有关联仓库

![图片](https://uploader.shimo.im/f/tYNAvQHDnRA6yjZ6.jpg!thumbnail)

### 6、 git remote add origin [https://github.com/scl1993/UpLoadFileStep](https://github.com/scl1993/UpLoadFileStep)
关联github仓库，并查看

![图片](https://uploader.shimo.im/f/wXfPWaJNi69KYYwz.jpg!thumbnail)

### **7、**** ****git pull 更新本地代码（同步本地代码）**
![图片](https://uploader.shimo.im/f/hxJiPMdfog39QNRt.jpg!thumbnail)

### **8、**** ****git push origin master 推送本地修改到远程仓库**
发现上面用了这个-u参数，也没作解释，特意搜索了下这个-u的用法，加了参数-u后，以后即可直接用git push 代替git push origin master

**git push -u origin master**

![图片](https://uploader.shimo.im/f/4uWLbB7g4dPT2xOA.jpg!thumbnail)

 

