# xbatch

批量部署/运维工具

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
> * [使用手册](https://github.com/BillWang139967/xbatch/wiki)
> * [提 Bug](https://github.com/BillWang139967/xbatch/issues/new)

### 版本发布
> * v1.6
>   * v1.6.2，2018-01-18, 修复：修复没有配置主机时，无法通过命令行进行配置
>   * v1.6.1，2018-01-17, 更新：新增 `hosts` 命令用于自动生成主机组以及主机 IP 列表（用于主机用户名以及端口一致时批量部署）,输出内容添加版本号
>   * v1.6.0，2018-01-17, 更新：`arch_ssh` ,`arch_put` 可以通过传入 IP 参数进行执行，同时调整部分目录结构
> * v1.5
>   * v1.5.6，2018-01-16, 更新：新增 `arch_ssh` ,`arch_put` 命令
>   * v1.5.5，2017-10-16, 更新：简化部分内容
>   * v1.5.4，2017-07-31, 更新：Useroot 项打开时，远端机器如果是root用户则直接执行
>   * v1.5.2，2017-07-27, 修复：安装时软连接指向错误问题
>   * v1.5.1，2017-04-16, 增加：xb sync 同步本地某文件到其他机器
>   * v1.5.0，2016-12-18, 更新：修改启动方式，将批量上传修改为 xshell 的 sftp 样式
> * v1.4
>   * v1.4.7，2016-10-07
> * v1.0
>   * v1.0.1，2015-01-01, 新增。发布初始版本。

### 小额捐款

如果你觉得 xbatch 对你有帮助，可以对作者进行小额捐助（支付宝）

![Screenshot](images/5.jpg)
