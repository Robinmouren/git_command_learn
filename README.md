记录使用git将项目上传到github   
并更新github上的项目  
  
rm -rf .git // 取消git init命令   
  
上传项目操作:  
git init // 初始化  
git add .   // 将项目添加到暂存区  .代表所有文件 若某个文件则是 xxxx.xxx  
git commit -m "注释内容"  
// 在github上新建一个仓库并复制地址  
git branch -M main //上传到main分支  
git remote add origin gttps://github.com/github名/仓库名  
git push -u origin main  
// 有时候需要token命令牌 在githun个人settings中的developer settings解决  
  
  
  
  
  
git status 查看状态  
更新操作：  
git add * //更新全部  
git commit -m "更新说明"  
git pull // 拉取当前分支最新代码  
git push origin main  //不是master  
