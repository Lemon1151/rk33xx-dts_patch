编译步骤：

需要一个ubuntu系统
拉取Armbian官方源代码到本地git clone --depth=1 --branch=main https://github.com/armbian/build
复制本仓库下所有文件到你本地build目录
cd build
./compile.sh

2024.04固件由ophub大佬的项目修改而来，替换了boot和rootfs重新打包，可以识别SATA，可以同步更新ophub内核
ophub项目地址：https://github.com/ophub/amlogic-s9xxx-armbian
