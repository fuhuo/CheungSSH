# by fuhuo
首先非常感谢@CheungSSH 写了这个运维工具，确实非常好用，希望这个工具越来越好，成为经典

我只是在其基础上作一些修改，已得原作者同意

修改项如下：
2015-06-28：

增加-c(--command)参数，修改了一些代码以符合PEP8

```
example：

cheungssh.py -g "group-name" -c "df -h"

cheungssh.py -o 127.0.0.1,127.0.0.2 -c "df -h"
```

2015-06-26:

同步了v119的vi支持

2015-06-25:

基于chungssh_v117版本在原作者的工具基础上增加了-g(--group)和-o(--host)选项，设定进入时选定的组或者IP

```
example：

cheungssh.py -g "group-name"

cheungssh.py -t upload -g "group-name" -s /local/file  -d /remote/dir
```

```
example：

cheungssh.py -o 127.0.0.1

cheungssh.py -o 127.0.0.1,127.0.0.2

cheungssh.py -g "group-name" -o 127.0.0.1
```

原作者的github：https://github.com/zhangqichuan/CheungSSH

原作者的话：

# CheungSSH
比Ansibel更好用的自动化工具

这是我（张其川 Cheung Kei-Chuen） 自主开发的基于 SSH协议的自动操作工具，比Ansible更轻量！操作更简单！

如果您觉得本软件还不错，有需要的话，请与我联系，包括有任何的使用疑问

我的QQ   2418731289

详细的用法介绍请： http://blog.chinaunix.net/uid-29295703-id-4663051.html

如果有任何试用疑问，请联系我！！
