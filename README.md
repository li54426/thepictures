# thepictures

### github使用指南

1.ssh
ssh-keygen -t rsa       #生成本地密钥
id_rsa.pub                  #将他添加到github
ssh -T git@github.com  进行测试

2.pull &push

git push origin main
git pull origin main




克隆
git clone git@github.com:li54426/test.git

git remote add origin 仓库名

git config --global alias.psm 'push origin master'
git config --global alias.plm 'pull origin master'



```
git config --global alias.lg "log --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit --date=relative"
```

```
添加
git add .

查看状态
git status

提交
git commit -m "Story 182: Fix benchmarks for speed"

忽略
git config --global core.excludefile ~/.gitignore
```




