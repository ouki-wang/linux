# 阿里云如何启动vsftpd
## 安装vsftpd
sudo apt-get install vsftpd
## 允许本地用户访问
/etc/vsftpd.conf
打开
local=ENABLE

## 防火墙允许21号端口
ufw allow 21/tcp

## 重启vsftpd
sudo /etc/init.d/vsftpd restart



## filezilla需要配置传输模式
传输设置->主动模式
