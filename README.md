# Usage:
```
git clone https://github.com/linux-downey/mk_binary_deb_demo.git
dpkg-deb -b mk_binary_deb_demo/ debhello_1.0.0-1.0_amd64.deb
```  

以下指令为安装deb包并运行程序，但是编译的bin文件为amd64架构，其他架构下程序不能正常运行
```  
sudo dpkg -i debhello_1.0.0-1.0_amd64.deb
hello_world
```





