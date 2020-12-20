```
git config  credential.helper store  
```

```
michaelhee@DESKTOP-FNSEB12 MINGW64 /e/code/vue3_project (dev)
$ git remote -v
origin  https://github.com/Michael1117/vue3_project.git (fetch)
origin  https://github.com/Michael1117/vue3_project.git (push)

michaelhee@DESKTOP-FNSEB12 MINGW64 /e/code/vue3_project (dev)
$ git remote rm origin

michaelhee@DESKTOP-FNSEB12 MINGW64 /e/code/vue3_project (dev)
$ git remote -v

michaelhee@DESKTOP-FNSEB12 MINGW64 /e/code/vue3_project (dev)
$ git remote add origin git@github.com:Michael1117/vue3_project.git

michaelhee@DESKTOP-FNSEB12 MINGW64 /e/code/vue3_project (dev)
$ git remote -v
origin  git@github.com:Michael1117/vue3_project.git (fetch)
origin  git@github.com:Michael1117/vue3_project.git (push)
```
```
ssh-keygen -t rsa -C "1322720377@qq.com"
```

```
michaelhee@DESKTOP-FNSEB12 MINGW64 ~/.ssh
$ cd /c/Users/michaelhee/.ssh/

michaelhee@DESKTOP-FNSEB12 MINGW64 ~/.ssh
$ ll

total 5
-rw-r--r-- 1 michaelhee 197121    0 12月 20 17:02 id_rsa
-rw-r--r-- 1 michaelhee 197121  399 12月 20 16:56 id_rsa.pub
-rw-r--r-- 1 michaelhee 197121 2786 9月  25 11:48 known_hosts

$ cat id_rsa.pub
ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABAQDoOe4pgCfHZHYxWyzNXeXKQ38cHt4HzJ8Wqd1oH+Ho45ZYK6KfiK5h4XgTWC0y0wLXOGq5SDkrucVRmZAz0u8e8fv9Gbjl/p6qgCtZ8Y1VSxzivQpytWcQjSX5ECcd4MrlhoWwkZKFYxG+xoQ/C/ZXwWxyyiBJnIxxYGFt6Cp+OzOeW+XwYzo03/
.....

```

## 将id_rsa.pub中的数据放入github中

git pull origin dev --allow-unrelated-histories


## git提交代码每次都要输入密码的解决方法

```
git config --global credential.helper store
```