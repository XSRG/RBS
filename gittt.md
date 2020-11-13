# gitub与本地文件夹链接
```cpp
echo "# RBS" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M master
git remote add origin https://github.com/XSRG/RBS.git
git push -u origin master
```  
# 上传
```cpp
    git init
    git status
    git commit -m "wocao"
    git push --rebase origin master
    git push -u origin master
```