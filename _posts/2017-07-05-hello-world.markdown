---
layout: post
title:  "Hello World!"
date:   2017-07-05 14:07:54 +0800
author: 赵鹏
categories: 
---

* Hello World!
* 文件命名方式： 年-月-日-标题.markdown
* 需要安装Git，Git Bash(Git安装时自带)。
* **初次**写博客流程：
  1. 打开git bash(git 自带的一个命令行)。
  2. 寻找并进入一个合适的目录，例如D盘根目录。使用 `cd d:/`。这个命令在不同版本系统下可能有差异。
  3. 输入git clone https://github.com/wilna-staff/wilna-staff.github.io.git
  4. 执行上一步操作成功后，会出现一个wilna-staff.github.io的文件夹。
  5. 进入该文件夹。
  6. 复制template.markdown 到`_post` 文件夹。
  7. 修改文件名和文件内容,并保存。
  8. 打开git bash，进入wilna-staff.github.io文件夹，执行如下命令。
  9. `git add .`。
  10. `git commit -m "你的提交信息(可以先随便写，等知道这是啥之后，再好好写。)"`。
  11. `git push`。
  12. 输入你的账户，密码，等待提交成功。
  13. 一两分钟后，可以访问[wilna-staff](https://wilna-staff.github.io)查看更新情况。
* step 1-4 是为了下载远程的代码到本地。
* step 5-13 则是博客的写作与发表流程。
* 非初次写博客，需要先在目录下执行`git pull`命令，然后一次执行5-13。
