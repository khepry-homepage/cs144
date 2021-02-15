telnet cs144.keithw.org http	//与主机的http服务建立tcp连接
GET /lab0/sunetid HTTP/1.1	//请求lab0目录下的sunetid文件
Host: cs144.keithw.org	//主机名
Connection: close	//指明非持续连接
多次按下回车结束此次链接，获取返回文本