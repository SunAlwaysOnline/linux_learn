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
netstat -lnp |grep 80  (-l 显示listen状态的端口,-n 拒绝显示别名,即将0.0.0.0:http显示为0.0.0.0:80,-p 显示相应的pid与程序名)

终止进程
kill -9 pid

由jar包查找进程号
ps aux | grep jar包名称 | grep -v grep | awk '{print $2}'  
grep -v grep 去除查找的进程号  
awk '{print $2}' 以空格分隔结果，直接得到进程号  

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
#### [Windows下安装MysQL5.6.36步骤](https://www.cnblogs.com/muhehe/p/7701989.html)

-------------------------------------------------
