# 用VMware17安装openEuler的教程

#### 1.安装配置

- Windows 11
- openEuler 22.03 LTS SP1
- VMware Workstation 17 Pro

<img src="https://raw.githubusercontent.com/fograinwater/PicGo-img/master/image-20231011162835095.png" alt="image-20231011162835095" style="zoom:67%;" />



#### 2.下载OpenEuler镜像

##### 2.1 在官网下载镜像【https://www.openeuler.org/zh/download/】

<img src="https://raw.githubusercontent.com/fograinwater/PicGo-img/master/image-20231011163009886.png" alt="image-20231011163009886" style="zoom:40%;" />

- **根据电脑型号选择对应版本**。查看电脑系统信息（win+R，输入dxdiag）：

![image-20231011163113769](https://raw.githubusercontent.com/fograinwater/PicGo-img/master/image-20231011163113769.png)



#### 3.创建虚拟机

##### 3.1 点击新建虚拟机，选择典型安装

<img src="https://raw.githubusercontent.com/fograinwater/PicGo-img/master/image-20231011163213821.png" alt="image-20231011163213821" style="zoom: 67%;" />

##### 3.2 选择稍后安装

<img src="https://raw.githubusercontent.com/fograinwater/PicGo-img/master/image-20231011163229308.png" alt="image-20231011163229308" style="zoom:67%;" />

##### 3.3 根据下载的openEuler版本选择客户机操作系统版本内核

- 查看openEuler 22.03 LTS版本内核信息

  <img src="https://raw.githubusercontent.com/fograinwater/PicGo-img/master/image-20231011163302742.png" alt="image-20231011163302742" style="zoom: 67%;" />

- （我下载的openEuler版本为22.03 LTS，所以选择Linux 5.x内核64位）

  <img src="https://raw.githubusercontent.com/fograinwater/PicGo-img/master/image-20231011163333176.png" alt="image-20231011163333176" style="zoom: 78%;" />

##### 3.4 自定义虚拟机名称“openEuler”，选择安装位置

<img src="https://raw.githubusercontent.com/fograinwater/PicGo-img/master/image-20231011163353124.png" alt="image-20231011163353124" style="zoom:67%;" />

##### 3.5 选择磁盘容量（20GB，将虚拟磁盘存储为单个文件即可）

<img src="https://raw.githubusercontent.com/fograinwater/PicGo-img/master/image-20231011163420728.png" alt="image-20231011163420728" style="zoom:67%;" />

##### 3.6 选择自定义硬件

<img src="https://raw.githubusercontent.com/fograinwater/PicGo-img/master/image-20231011163435597.png" alt="image-20231011163435597" style="zoom:67%;" />

##### 3.7 将下载好的openEuler镜像添加至新 CD/DVD(IDE)（根据自己下载的ISO文件路径来选择）

<img src="https://raw.githubusercontent.com/fograinwater/PicGo-img/master/image-20231011163455175.png" alt="image-20231011163455175" style="zoom:67%;" />

##### 3.8 分配1P（处理器数量），2C（每个处理器的内核数量）

<img src="https://raw.githubusercontent.com/fograinwater/PicGo-img/master/image-20231011163522798.png" alt="image-20231011163522798" style="zoom:67%;" />

##### 3.9 分配2G内存即可

<img src="https://raw.githubusercontent.com/fograinwater/PicGo-img/master/image-20231011163538301.png" alt="image-20231011163538301" style="zoom:70%;" />

##### 3.10 关闭以后点击完成即可。



#### 4. 安装OpenEuler

##### 4.1 点击开启此虚拟机

<img src="https://raw.githubusercontent.com/fograinwater/PicGo-img/master/image-20231011163748961.png" alt="image-20231011163748961" style="zoom:40%;" />

##### 4.2 选择第一个install，按回车即可

<img src="https://raw.githubusercontent.com/fograinwater/PicGo-img/master/image-20231011163818124.png" alt="image-20231011163818124" style="zoom:80%;" />

##### 4.3 选择语言

<img src="https://raw.githubusercontent.com/fograinwater/PicGo-img/master/image-20231011164015891.png" alt="image-20231011164015891" style="zoom: 80%;" />

##### 4.4 选择安装目的地

<img src="https://raw.githubusercontent.com/fograinwater/PicGo-img/master/image-20231011164148531.png" alt="image-20231011164148531" style="zoom:80%;" />

##### 4.5 因为我们大小只给了 16 G，并且选择的是存储单个文件，所以直接选择“完成”即可

<img src="https://raw.githubusercontent.com/fograinwater/PicGo-img/master/image-20231011164104246.png" alt="image-20231011164104246" style="zoom:80%;" />

##### 4.6 点击配置网络

<img src="https://raw.githubusercontent.com/fograinwater/PicGo-img/master/image-20231011164238435.png" alt="image-20231011164238435" style="zoom:80%;" />

##### 4.7 选择将网络打开

<img src="https://raw.githubusercontent.com/fograinwater/PicGo-img/master/image-20231011164313542.png" alt="image-20231011164313542" style="zoom: 80%;" />

##### 4.8 设置root密码

<img src="https://raw.githubusercontent.com/fograinwater/PicGo-img/master/image-20231011164423256.png" alt="image-20231011164423256" style="zoom:80%;" />

##### 4.9 要求密码包含大小写，密码填写无误后点击左上角“完成”

<img src="https://raw.githubusercontent.com/fograinwater/PicGo-img/master/image-20231011164631908.png" alt="image-20231011164631908" style="zoom:80%;" />

##### 4.10 可以创建一个普通用户（也可以安装后通过命令创建）

<img src="https://raw.githubusercontent.com/fograinwater/PicGo-img/master/image-20231011164803209.png" alt="image-20231011164803209" style="zoom:80%;" />

##### 4.11 为普通用户设置密码

<img src="https://raw.githubusercontent.com/fograinwater/PicGo-img/master/image-20231011164849215.png" alt="image-20231011164849215" style="zoom:80%;" />

##### 4.12 点击开始安装

<img src="https://raw.githubusercontent.com/fograinwater/PicGo-img/master/image-20231011164910869.png" alt="image-20231011164910869" style="zoom:80%;" />

##### 4.13 安装完成后选择重启系统

##### 4.14 用刚刚设置的密码登录root用户，显示如下信息就是安装成功了

![image-20231011170358532](https://raw.githubusercontent.com/fograinwater/PicGo-img/master/image-20231011170358532.png)

##### 4.15 如果原显示字体太小还可以选择VM左上角“查看”——>选择“拉伸客户机”—>“保持丛横比拉伸”，观感更好

<img src="https://raw.githubusercontent.com/fograinwater/PicGo-img/master/image-20231011170448060.png" alt="image-20231011170448060" style="zoom: 50%;" />

以上就是用VMware Workstation 17 Pro安装openEuler的全部流程。