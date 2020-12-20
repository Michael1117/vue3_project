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

ssh-keygen -t rsa -C "1322720377@qq.com"