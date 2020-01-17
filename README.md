# NanoRTOS
A real time operating system for personal use.

/*==============================================================================================
	
	By HYH
	https://github.com/List-View/NanoRTOS
	创建时间-2019/01/28
	最后修改时间-
	文件名-readme.txt
	文本编码-utf-8
	--------------------------------------------------------------------------------------------
	当前版本号-NanoRTOS V0.01.1 2019/08/27
	
	历史版本------------------------------------------------------------------------------------
	2017/10/10---简易延时定时任务控制器 Demon版本 V0.0
	2018/01/21---状态机延时组件控制器 测试版 V1.1/V1.1/V1.2 正式版 V1.3
	2018/01/23---重组为任务控制器 TC V0.0/V1.0/V1.01/V1.2
	2018/02/12---任务控制器稳定版(TC-V1.21) 正式版
	2018/10/05---优化版本为TC-V2.0----失败
	2019/01/28---重组为NanoRTOS V0.0 Demon版
	2019/08/27---添加改进代码结构 NanoRTOS V0.01.00
	2019/08/31---做了小修改 NanoRTOS V0.01.01
	--------------------------------------------------------------------------------------------
	
	--------------------------------------------------------------------------------------------
	
	历史各个版本详细改动:
	2019/01/28--V0.00.0:Demon内测版本
	2019/08/27--V0.01.0:改进了代码的格式与注释，添加了sys_interface接口，方便后面的多应用开发的
		实现，添加了LemonGUI(微型嵌入式GUI框架)/mini-L2L(嵌入式数据传输控制协议)/LiteUDB(嵌
		入式微型数据存储方案框架)三个组件的支持(可独立移植),添加了内存管理组件.代码可以在MCU/Linux
		/Windows下编译通过可移植。添加了系统interface支持，将会实现外部独立应用文
		件加载到内存运行.
	
	下一版本将会考虑加入的新特性
	4.具备某一程度的任务优先级调度，使得重要的任务能够尽可能优先执行
	5.添加基于协程的实现
	6.添加线程的实现
	7.添加bin文件的app加载运行
	8.任务调度器添加时间片轮询法/优先级剥夺等任务调度方法
	9.添加互斥锁/信号量/邮箱等任务同步及任务间通信的方式
	
==============================================================================================*/
	
	


