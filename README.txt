使用最初需要将debug.exe所在的目录挂载为C:盘
mount c E:\Debug
C:
debug

每次进入DosBox都要操作一遍很麻烦，可以在DOS安装下的Option文件夹下找到DOSBox 0.74-3 Options，打开
在autoexec配饰段中配置，如下
[autoexec]
# Lines in this section will be run at startup.
# You can put your MOUNT lines here.

mount c E:\Debug
C:
debug
