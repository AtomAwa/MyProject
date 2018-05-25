---
title: git上传到github教程
date: 2018-05-24 22:48:15
tags:
categories: "git教程"
---

or create a new repository on the command line
echo "# JinYuCode" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/AtomAwa/JinYuCode.git
git push -u origin master

or push an existing repository from the command line
git remote add origin https://github.com/AtomAwa/JinYuCode.git
git push -u origin master
