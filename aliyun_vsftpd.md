sudo apt-get install vsftpd

/etc/vsftpd.conf
打开
local=ENABLE

防火墙允许21号端口
ufw allow 21/tcp

重启vsftpd
sudo /etc/init.d/vsftpd restart



filezilla
传输设置->主动模式