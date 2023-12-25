# Git学习日志

#### 记录学习使用git过程中常使用的命令操作以及问题



**rm -rf .git** ——取消git init命令   



**上传项目操作**:

* **git init**  ——仓库初始化

* **git add .**   ——将项目添加到暂存区  .代表所有文件 若某个文件则是 xxxx.xxx 

* **git commit -m "注释内容"** 

* 在github上新建一个仓库并复制地址 

* **git branch -M main** ——上传到main分支 

* **git remote add origin https://github.com/github名/仓库名** 

* **git push -u origin main** ——上传到远程仓库

* 有时候需要token命令牌 在github个人settings中的developer settings解决 



**git status** 查看状态 



**更新操作**：

* **git add *** ——更新全部 

* **git commit -m "更新说明"** 

* **git pull**  —— 拉取当前分支最新代码 

* **git push origin main**  ——或者master



### 从远程仓库中拉取项目

* **git clone + 仓库地址**

* cd 切换到项目

* dir查看项目结构

* **git pull origin main** ——准备更新

* **git rm -r -cached + 想要删除的文件名**

* **git commit -m "提交说明"**

* **git push -u origin main** —— 提交到远程仓库





### git bash 代理问题

* 针对github.com本身
  * **git config --global http.https://github.com.proxy 'http://127.0.0.1:代理的port'**

* 取消代理
  * **git config --global --unset http.https://github.com.proxy**
