# 软件使用中的技巧



## cmd:

### 内网发送信息

```
MSG /server:内网ip * "找你没事情，下午出去玩吧"
```

### 查看当前所有连接过的wifi密码

```
netsh wlan show profiles

netsh wlan show profile name="" key=clear
```

### 查看ip和自己的外网地址

```
ipconfig /all
curl -L ip.tool.lu
```

### 远程控制

```
mstsc
```

### 修改字体颜色

```
color all
color a
永久修改
regedit编辑查找DefaultColor
数据数值改成a
```

### 查看电脑上的用户防入侵

```
net user
net user name /del
```

### 电脑卡检查系统完整性

```
sfc /SCANNOW
```



## 网络ip

```
cip.cc
```



## typora设置图片相对路径

![image-20230408172522710](img/image-20230408172522710.png)



![image-20230408173829879](img/image-20230408173829879.png)





## pr打不开 报错

```
Application Specific Information:
C:\Program Files\Adobe\Adobe Premiere Pro CC 2018\ZXPSignLib-minimal.dll



Thread 0 Crashed:	[18148]	THREAD_PRIORITY_NORMAL
0	ZXPSignLib-minimal  0x00000000056473e3 ? Unknown - (Symbols generated from a DLL export table)	[  Error:487 试图访问无效的地址。 ]
1	 ???? (  Error: 126 找不到指定的模块。 ) 0x00000000527a4d77 ? Unknown - ()	[  Error:126 找不到指定的模块。 ]
```

把pr中的文件复制到安装目录替换