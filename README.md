# BMGR_SOD_code
Salient object detection method by combining Boolean map and grayscale rarity
代码为《结合布尔图和灰度稀缺性的小目标显著性检测》一文的源代码。
作者：李楚为，张志龙，杨卫平。
单位：国防科技大学。
引用格式：李楚为,张志龙,杨卫平.结合布尔图和灰度稀缺性的小目标显著性检测[J].中国图象图形学报,2020,25(02):267-281.

配置要求：
windows系统；opencv2.40及以上版本；matlab2012及以上版本或visual studio 2010及以上版本。

有两种使用方式：
1、使用matlab：
	1）在mex文件夹下的compile.m中添加opencv所在路径库；
	2）运行“compile.m”，等待编译成功（十几秒）；
	3）运行“demo.m”

2、使用VS
	1）新建一个win32控制台应用程序，设置为Debug，x64模式；
	2）配置好opencv环境；
	3）复制BMGR.h文件和BMGR.cpp文件到文件夹下，“添加现有项”；
	4）将main函数的cpp替换为BMGR_main.cpp中的内容；
	5）建立“src”文件夹，放入输入图像；建立“smap”文件夹，输出显著图；
	5）F7编译，F5运行。

输入文件夹：src
输出文件夹：smap
耗时结果	：run_time.txt
