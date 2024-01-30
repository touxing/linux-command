setenforce
===

SElinux 在linux内核级别上提供了一个灵活的强制访问控制系统(MAC)，这个强制访问控制系统是建立在自由访问控制系统(DAC)之上的。

###  语法

```shell
setenforce <参数>
```

#### 参数：

|参数|作用|
|----|----|
| 0 | 设置SELinux 成为permissive模式|
| 1 | 设置SELinux 成为enforcing模式|

### 例子

设置当前SELinux的应用模式。

```shell
[root@localhost ~]# setenforce 0 #设置SELinux 成为permissive模式
[root@localhost ~]# setenforce 1 #设置SELinux 成为enforcing模式
```

相关命令： **getenforce**
