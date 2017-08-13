###一、SSH连接Git服务器
1. 设置Git的user.name和user.email<br>
  ` $ git config --global user.name "humingx"`
   `$ git config --global user.email "humingx@yeah.net"`
2. 生成密钥<br>
	$ ssh-keygen -t rsa -C "humingx@yeah.net"