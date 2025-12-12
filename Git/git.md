### 1. 下载

```bash
git  clone  https://github.com/用户名/仓库名.git
cd  仓库名
```

**先删除文件夹下的.git, .gitmodules ! ! !**
```bash
#查看
ls -A
```

### 2. 登入
```bash
git config --global user.name "J-X-Chen"
git config --global user.email "1193739898@qq.com"
```

### 3. 更新仓库(拉最新的)
```bash
git pull origin main
```
 
### 4. 创建分支
```bash
git branch feature/新分支
git checkout feature/新分支
git branch
#看是否切换到新分支上
```

### 5. 添加与上传
```bash
git  add  .
git  commit  -m  "update"
git  push  origin  feature/新分支
```

### 6. 合并rp(要权限)
该过程在网页一直merge即可
  
### 其他删除操作
- 删除内容
```bash
git  rm  要删除的文件夹/  -r  --cached
git  commit  -m  "delate"
git  push  origin  feature/新分支
```

### Github官方建议
```bash
echo "# Note" >> README.md 
git init git add README.md 
git commit -m "first commit" 
git branch -M main 
git remote add origin https://github.com/J-X-Chen/Note.git 
git push -u origin main 

or 

git remote add origin https://github.com/J-X-Chen/Note.git 
git branch -M main 
git push -u origin main
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE5MTY1MDA5NDJdfQ==
-->