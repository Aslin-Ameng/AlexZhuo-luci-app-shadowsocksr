OpenWrt/LEDE  LuCI for ShadowsocksR
===
此文是为AlexZhuo的luci-app-shadowsocksr和luci-app-pdnsd以及pdnsd的文件而写
首先luci-app-shadowsocksr添加了最新协议auth_chain_a  auth_chain_b  auth_chain_c  auth_chain_d 
虽说后面的C D不能用但是都添加了 以及添加了tls1.2_ticket_fastauth混淆 这个ssr只是添加协议和混淆而已  
而比较重要的就是在我这个仓库里面有个pdnsd的文件夹下pdnsd/files/pdnsd.init这里面原本是有代码的就是因为有代码导致编译好是有限获取不了ip的
而把这里pdnsd.init里面清空在编译就行 我在上传这个文件的时候里面必须写入文字不然不然上传我了个擦 请看到此文章的朋友记得清空哦 


这很重要 这很重要 这很重要
==
在嘱咐下记得清空pdnsd/files/pdnsd.init 这个pdnsd.init里面的所有东西保存即可
