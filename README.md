![image](https://github.com/yuanyunqiang/MxPi/blob/main/mx-raspberry-pi/mxpi/static/img/logo.png?raw=true)
#### 1. Installation
Use pip to install and update the latest version

###### Windows
```
pip install -U mxpi
```
###### Liunx(Raspberry Pi)

```
sudo pip3 install -U mxpi
```
#### 2. Use
Run the following command in Terminal:

```
#Windows
mxpi
#Liunx or Raspberry Pi
sudo mxpi
```
After running, you will get the following information:

```
Welcome to MxPi(0.0.xx)!  System:xxxxx   IP: x.x.x.x:xxxx
2022-02-11 15:56:10,412 INFO     Starting server at tcp:port=80:interface=192.168.1.129
2022-02-11 15:56:10,414 INFO     HTTP/2 support not enabled (install the http2 and tls Twisted extras)
2022-02-11 15:56:10,415 INFO     Configuring endpoint tcp:port=80:interface=192.168.1.129
2022-02-11 15:56:10,418 INFO     Listening on TCP address x.x.x.x:xxxx
```
Open IP address ++x.x.x.x:xxxx++ in browser

![image](https://github.com/yuanyunqiang/MxPi/blob/main/img/mxpi.png?raw=true)
#### 3. Description
If you use Windows to uninstall or update the latest version of MxPi, the following error will occur

```
UnicodeDecodeError: 'utf-8' codec can't decode byte 0xd0 in position 12091: 
invalid continuation byte in installed-files.txt file at path: 
xxx/installed-files.txt
```
This is due to the default encoding of the system. This problem is not caused by MxPi. You can open the xxx/installed-files.txt file and change the encoding mode to UTF-8, and then uninstall or update it again.


#### 4. Update information
##### Version : 0.0.36
1. Add PyQt5 related modules
2. Add file management function
3. Fixed the problem of encoding error under Windows
4. The output of library management information is more reasonable
5. Modified the content in about

#### 5. Plan
- [ ] Added Baidu AI related modules
- [ ] Add PyQt multithreading module
- [ ] Add temperature sensor module
- [ ] Added support for exporting py files






