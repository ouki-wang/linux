# Adduser
---------------------------------------------------------
* 注意要用adduser 不要用useradd
  adduser zhangsan
* 将用户添加到root组
  usermod -g root zhangsan
* 修改/etc/sudoers
   chmod +w /etc/sudoers
   vim /etc/sudoers
   添加这行  zhangsan   ALL=(ALL:ALL) ALL
   chmod -w /etc/sudoers
   
