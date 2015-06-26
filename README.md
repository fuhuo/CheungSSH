# by fuhuo
同步了v119的vi支持
基于chungssh_v117版本在原作者的工具基础上增加了-g和-o选项，设定进入时选定的组或者IP

cheungssh.py -g "group-name"
cheungssh.py -t upload -g "group-name" -s /local/file  -d /remote/dir



cheungssh.py -o 127.0.0.1
cheungssh.py -o 127.0.0.1,127.0.0.2
cheungssh.py -g "group-name" -o 127.0.0.1


原作者的话：

# CheungSSH
比Ansibel更好用的自动化工具
这是我（张其川 Cheung Kei-Chuen） 自主开发的基于 SSH协议的自动操作工具，比Ansible更轻量！操作更简单！
如果您觉得本软件还不错，有需要的话，请与我联系，包括有任何的使用疑问
我的QQ   2418731289

详细的用法介绍请： http://blog.chinaunix.net/uid-29295703-id-4663051.html
如果有任何试用疑问，请联系我！！
