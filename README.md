# AsRock-Z490i-Phantom-ITX-TB3
AsRock-Z490i-Phantom-ITX-TB3 OpenCore
一、配置详情：
主       板：ASRock Z490 Phantom Gaming-ITX/TB3

C   P  U  ：  i5   10500
电      源 ：全汉600W
独立显卡：蓝宝石RX5600xt 
无线网卡：博通94360NG 
内       存：Kingston  FURY 8G X2 3200RGB（双通道）
硬       盘1：M.2 西部数据 （Western Digital） SN750       500G
硬       盘2：M.2 西部数据 （Western Digital）SN750SE   500G
二、使用状况：
1、睡眠、唤醒正常；投送、随行正常。
2、BCM94360NG 无线网卡正常，2.5Gbit以太网：Realtek RTL8125B-CG正常。
3、雷电3驱动已加载，未刷芯片“关于本机”不会显示。
4、成功开启节能四项。
三、OC引导更新介绍：
2022-2-10
1、同步HackinPlugins_20220210文件
2、OC版本升级为“OC0.7.9”
3、已更新macOS Monterey 12.3 Beta版(21E5206e),通用控制功能很给力。

2022-3-3
1.同步HackinPlugins_20220303文件
2.修复了启用AVX加速时可能出现的内存报错
3.添加日志模块，用于按模块进行正向和反向日志过滤
4.支持从独立/boot分区启动Linux，而不使用/loader/entries文件
5.在驱动程序参数中处理XML实体
6.将OpenLinuxBoot驱动程序参数partuuidpts:{PARTUUID}命名为autoopts:{PARTUUID}
2022-3-08
1.同步HackinPlugins_20220310文件
2.EFI文件内附OCC0.8.0编辑器
