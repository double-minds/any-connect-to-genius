安装ss服务器
============
>1. sudo apt-get install python-pip
>2. sudo pip install shadowsocks

启动服务器
=========
>sudo ssserver -p 443 -k 123abc123 -m aes-256-cfb -d start
（-p代表端口，-k代表密码，-m代表加密模式）
