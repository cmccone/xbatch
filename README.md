# xbatch

批量运维工具

* [使用手册](https://github.com/BillWang139967/xbatch/wiki)
* [版本发布](#版本发布)
* [小额捐款](#小额捐款)

### 架构

```
     +------+  +------+  +------+
     |server|  |server|  |server|
     +------+  +------+  +------+
             \    |    /<-------------------------ssh
               +------+
               |xbatch|
               +------+
```

### 版本发布

* v1.5.4，2017-07-31, 更新：Useroot 项打开时，远端机器如果是root用户则直接执行
* v1.5.2，2017-07-27, 修复：安装时软连接指向错误问题
* v1.5.1，2017-04-16, 增加：xb sync 同步本地某文件到其他机器
* v1.5.0，2016-12-18, 更新：修改启动方式，将批量上传修改为 xshell 的 sftp 样式
* v1.4.7，2016-10-07
* v1.0.1，2015-01-01, 新增。发布初始版本。

### 小额捐款

如果你觉得 xbatch 对你有帮助，可以对作者进行小额捐助（支付宝）

![Screenshot](images/5.jpg)
