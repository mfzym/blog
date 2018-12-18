---
title: 初识github
date: 2018-11-30 20:33:56
tags: 杂
categories: 杂
---
尝试开始用github托管代码，记录一下常用命令

<!--more-->

#### 建立git库

```c
echo "# Test" >> README.md
git init
git add .
git add README.md
git commit -m "注释语句"
git remote add origin https://github.com/******
git pull origin master
git push -u origin master
```

#### 更新代码

```c
git status
git add *
git commit -m "更新说明"
git pull
git push origin master
```



