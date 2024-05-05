## 编译步骤：
1.需要一个ubuntu系统  
2.拉取Armbian官方源代码到本地  git clone --depth=1 --branch=main https://github.com/armbian/build  
3.复制本仓库下所有文件到你本地build目录  
4.cd build  
5.执行compile.sh脚本选择型号进行编译  
项目内容根据https://github.com/cm9vdA/build-armbian   仓库修改而来  
Armbian官方源码仓库地址：https://github.com/armbian/build  
**官方源代码编译的小宝固件可以正常使用SATA**  
  

  
## Armbian_xiaobao_SATA_2024
2024固件由ophub大佬的项目修改而来，替换了boot和rootfs重新打包，可以识别SATA，可以同步更新ophub内核
ophub仓库地址：https://github.com/ophub/amlogic-s9xxx-armbian
