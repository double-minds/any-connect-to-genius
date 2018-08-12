修改SSH Port
============
>1. sed -i '$d' fileName  删除最后一行
>2. echo “Port 22” >> /etc/ssh/sshd_config  修改SSH Port端口

安装ss服务器
============
>1. sudo apt-get -y install python-pip
>2. sudo pip install shadowsocks

启动服务器
=========
>sudo ssserver -p 443 -k 123abc123 -m aes-256-cfb -d start
（-p代表端口，-k代表密码，-m代表加密模式）
