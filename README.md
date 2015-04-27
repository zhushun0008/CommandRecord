1. Linux Command
===================
1. Add a user
[The difference between adduser and useradd](http://blog.csdn.net/hbsong75/article/details/9246669)

We could create userName/password within []. 
```
sudo adduser [userName]
sudo [password] userName
```
2. Monitor all Processes
ps -aux
The detail explanation in this site[http://blog.csdn.net/hanner_cheung/article/details/6081440]
3. Re-Directing
     * 标准输入   (stdin) ：代码为 0 ，***使用 < 或 <<*** ； /dev/stdin -> /proc/self/fd/0   0代表：/dev/stdin 
     * 标准输出   (stdout)：代码为 1 ，***使用 > 或 >>*** ； /dev/stdout -> /proc/self/fd/1  1代表：/dev/stdout
     * 标准错误输出(stderr)：代码为 2 ，***使用 2> 或 2>>*** ； /dev/stderr -> /proc/self/fd/2 2代表：/dev/stderr
     * &[n] 代表是已经存在的文件描述符
          * &1 代表输出 &2代表错误输出 
          * &-代表关闭与它绑定的描述符
     * Reference:
          * [linux shell数据重定向（输入重定向与输出重定向）详细分析](http://www.cnblogs.com/chengmo/archive/2010/10/20/1855805.html)

4. nohup help to run the process in the back 
    * [在ssh、telnet断开之后继续执行程序](http://blog.chinaunix.net/uid-2623904-id-76976.html)
    * ps -A 
        * All process will be listed espeically for them in the back
        * Then kill the nohup process


2. Windows Command
===================
