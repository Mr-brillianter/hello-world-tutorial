"# hello-world-tutorial" 



what git recoomend to do

```
echo "# hello-world-tutorial" >> README.md

初始化
git init
将这个文件加入git
git add README.md
修改提交本地
git commit -m "first commit"
move移到分支
git branch -M main
添加远程仓库源
git remote add origin https://github.com/Mr-brillianter/hello-world-tutorial.git
提交远程仓库
git push -u origin main
```



# useful

1.初始化

git init

2.向git添加文件，前提已经写好

git add xxx

查看git状态

git status



3.修改提交

git commit -m "xxx"

没有-m会code报错

4.git push

推送到远端，第一次需要设置origin



## 问题

git不跟踪空文件夹



