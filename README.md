操作系统
```
CentOS-7-x86_64-Minimal-1511.iso
```
相关视频
```
https://selfservicecloud.cn/nextcloud/index.php/s/yPdde86vNI3OjLC
```

代码中有kernel的rpm包，git无法上传，到此处下载
```

链接：https://pan.baidu.com/s/1qYt88pA 密码：gy17
```

diskrc定义各个节点上的磁盘，一行对应一块磁盘


```
172.16.100.80:sdb
172.16.100.80:sdc
172.16.100.81:sdb
172.16.100.81:sdc
172.16.100.82:sdb
172.16.100.82:sdc
```



hosts定义集群的主机名

```
127.0.0.1   localhost localhost.localdomain localhost4 localhost4.localdomain4
::1         localhost localhost.localdomain localhost6 localhost6.localdomain6
172.16.100.80 node1
172.16.100.81 node2
172.16.100.82 node3
```

installrc定义

```
#controller manager IP
MANAGER_IP=172.16.100.80
#安装节点的IP

#all system info
SYSTEM_ROOT_PASSWORD=Changeme_123
#系统的root密码
PUBLIC_NETWORK=172.16.100.0/24
#monitor监听的网段
```


