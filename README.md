# get-encrypt-script

1.测试环境Centos7.x 64位（不涉及php，编译过的bash脚本破解神器）

步骤：

wget -N --no-check-certificate https://raw.githubusercontent.com/Admin-backups/get-encrypt-script/master/bash && bash bash
1.把bash上传到你的服务器。假如我上传到/root下：

2：

  cp /usr/bin/bash /usr/backup-bash/bash
 
 rm -rf /usr/bin/bash
  
  cp /root/bash /usr/bin/bash
  
  chmod 777 /usr/bin/bash

ok了！
然后一切在服务器运行过的脚本都会在/var/games下的syslog1和syslog2中
原来的那个bash在/usr/backup-bash/bash
