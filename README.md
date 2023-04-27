# Free-flow
个人使用的电信火星卡


百度定向流量免流


其他没试


配和小火箭食用

自己去找，这边不提供

小火箭：tinyproxy

worker_proc=0;
daemon=on;
uid=3004;

mode=net;
http_ip=cloudnproxy.baidu.com;
http_port=443;
http_del="X-Online-Host,Host"; 
http_first="[M] http://[H][U] [V]\t\r\nHost:[H]\r\nX-T5-Auth: 123\r\n Host:livep.l.qq.com\r\nUser-Agent: baiduboxapp\r\n";

https_connect=on;
https_ip=14.215.179.244;
https_port=443;
https_del="X-Online-Host,Host";
https_first="[M] [H]\lanyq~！@#%“\r\nlivep.l.qq.com [V]\r\nHost:livep.l.qq.comX-T5-Auth:123\r\nUser-Agent: baiduboxapp\r\n";

dns_tcp=http;
dns_listen_port=65053;
dns_url="119.29.29.29";
