# Linux Commands

## 进程

Q 杀死PID为123的进程

A kill -9 123

Q 查看端口号为123对应的pid

A netstat -anp | grep 123。a表示列出所有选项，n表示用数字表示，p表示列出进程名。

Q 杀死以test_app开始的进程名

A pgrep test_app | xargs kill -9

Q xargs的含义

A 作为参数，和grep比较相似。但是grep是作为输入，xargs是作为参数。

Q 后台运行abc这个程序

A abc &

## 重定向

Q 执行a程序将错误与标准输出都保存在a.txt中

A ./a >a.txt 2>1&

## 文件

Q 在当前目录创建一个软连接b.txt,链接到/home/renwang/a.txt

A ln -s /home/renwang/a.txt b.txt

Q 在当前目录下查找a.h的位置

A find . -name 'a.h'

Q 显示所有的文件,包含隐藏文件

A ls -a

## 排查日志

Q 监听a.log的最后100行

A tail -100f a.log



