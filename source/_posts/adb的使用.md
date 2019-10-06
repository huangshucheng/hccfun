---
title: 使用adb查看安卓日志
---


夜神模拟器  到安装bin目录下面 执行命令：（日志过滤）

 nox_adb.exe logcat | find "xxx"  >D:\yeshenmnq\Nox\bin\log.txt



手机的话也用普通的adb 命令就好了

直接输出到命令行：adb logcat 

输出到文件：adb logcat > log.txt



adb 重启：

adb kill-server

adb start-server