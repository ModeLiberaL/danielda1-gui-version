# danielda1-gui-version
# 为docker-danielda1增加了gui
# 首先载入镜像
# docker load -i danielda1-gui.tar
# 安装并开启 VcXsrv：首先https://chocolatey.org/安装chocolatey在本机
# 添加path环境变量C:\ProgramData\chocolatey\bin
# choco -v以确认是否安装成功
# 然后在powershell中choco install vcxsrv
# 安装后，在开始菜单搜索 "XLaunch"，启动后按以下步骤设置：
# 第1步	选择 Multiple windows
# 第2步	选择 Start no client
# 第3步	✅ 勾选 Disable access control（允许任何主机连接）
# 最后	点击 Finish 启动
# 随后
# 配置 Windows → Docker GUI 通信（设置 DISPLAY 环境变量）
# 因为是进入已有容器
# 在powershell中输入：export DISPLAY=host.docker.internal:0.0
之后：
# nautilus /DaRL/UGAT_Docker



#提取码：我用夸克网盘分享了「danielda1-gui.tar」，点击链接即可保存。打开「夸克APP」，无需下载在线播放视频，畅享原画5倍速，支持电视投屏。
链接：https://pan.quark.cn/s/1d9a19482013
提取码：gur5



