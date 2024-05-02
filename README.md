## 编译步骤：
1.需要一个ubuntu系统  
2.拉取Armbian官方源代码到本地  git clone --depth=1 --branch=main https://github.com/armbian/build  
3.复制本仓库下所有文件到你本地build目录  
4.cd build  
5../compile.sh  


##2024.04标签
2024.04固件由ophub大佬的项目修改而来，替换了boot和rootfs重新打包，可以识别SATA，可以同步更新ophub内核
ophub项目地址：https://github.com/ophub/amlogic-s9xxx-armbian
