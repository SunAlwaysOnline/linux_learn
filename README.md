## linux_learn
学习linux的日常记录

## linux命令篇
-------------------------------------------------
### 运行jar包

运行jar包，指定端口为80
java -Dserver.port=80 -jar  *****.jar

后台运行jar包
nohup java -jar *****.jar > /root/logs/a.log &

实时查看日志
tail -f a.log

查看80端口占用
netstat -ln |grep 80  (l 显示listen状态的端口,n 拒绝显示别名,即将0.0.0.0:http显示为0.0.0.0:80)

终止进程
kill -9 pid
-------------------------------------------------






## linux功能安装篇
-------------------------------------------------
### curl
#### [CentOS 7 更新 curl 为最新版本](https://www.htcp.net/337.html)

-------------------------------------------------
### jdk
#### [centos安装jdk1.8的三种方法](https://blog.csdn.net/dhr201499/article/details/81626466)

-------------------------------------------------
### mysql
#### [CentOS7安装MySQL（完整版）](https://blog.csdn.net/qq_36582604/article/details/80526287)

-------------------------------------------------
