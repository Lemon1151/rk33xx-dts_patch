## Armbian编译：
1.需要一个ubuntu系统  
2.拉取Armbian官方源代码到本地  git clone --depth=1 --branch=main https://github.com/armbian/build  
3.复制本仓库下所有文件到你本地build目录(或者复制patch补丁到对应的patch目录)  
4.cd build  
5.执行compile.sh脚本选择型号进行编译(第一次编译建议下内核kernel)  
Armbian官方源码仓库地址：https://github.com/armbian/build  
**官方源代码编译的小宝固件可以正常使用SATA**  
