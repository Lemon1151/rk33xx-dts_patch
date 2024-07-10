## Armbian编译：
1.需要一个ubuntu系统  
2.拉取Armbian官方源代码到本地  git clone --depth=1 --branch=main https://github.com/armbian/build  
3.复制本仓库下所有文件到你本地build目录(或者复制patch补丁到对应的patch目录)  
4.cd build  
5.执行compile.sh脚本选择型号进行编译(第一次编译建议编译下内核kernel)  
6.如果编译出来boot目录没有相关型号dts，自行给Makefile添加相关型号dtb  
Armbian官方源码仓库地址：https://github.com/armbian/build  
