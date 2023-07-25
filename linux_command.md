# 查询命令
## 用户态内核态包信息查询
|作用|命令|
|----|----|
|查询内核态模块|`lsmod \| grep <mod partname> ` |
|查询特定内核模块信息|`modinfo <modname>`|
|查询用户态的软件包|`rpm -qa \| grep <package partname>`|
|内核版本查询| `uname -r`|
## 系统运行信息查询
|作用|命令|
|---|---|
| 进程查询 | `ps` |
| 系统信息查询 | `top`|

# 修改命令
## 安装软件包
|作用|命令|
|---|---|
|安装二进制rpm文件| `rpm -i xxx.rpm`|
|编译源rpm文件| `rpmbuild --rebuild xxx.src.rpm` |
|使用yum在镜像库中安装包|`yum install <package name>`|
## 文件修改
|作用|命令|
|---|---|
|新建目录|`mkdir`|

# vim的使用
|作用|命令|
|---|---|
|vim打开文档| `vim <filepath>`|
|进入编辑模式|`i`|
|退出编辑模式|`Esc`|
|进入命令行模式|在退出编辑模式的情况下按`:`|
|不保存退出文档|在命令行模式输入`q!`|
|保存并退出文档|在命令行模式输入`wq`|


