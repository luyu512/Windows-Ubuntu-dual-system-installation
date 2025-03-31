# Windows+Ubuntu双系统安装

## *PS: ubuntu 20.04及以下版本安装完成后会有概率导致驱动不兼容情况（博主电脑因此不得不安装usb网卡），故建议选择22.04及以上系统*

## 第一步：下载Ubuntu镜像

如果我们使用官网进行下载，会因为网络问题导致下载时长过慢，故我们使用清华源镜像：https://mirrors.tuna.tsinghua.edu.cn/ubuntu-releases/

选择所需版本（此教程选用20.04）
![images](https://github.com/luyu512/ubuntu-/blob/main/Screenshots/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE%202025-03-30%20151922.png)

双击所需版本，进入下载页面
![images](https://github.com/luyu512/ubuntu-/blob/main/Screenshots/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE%202025-03-30%20151909.png)

选择后缀为“desktop-amd-64.iso”的镜像下载

## 第二步：下载Rufus来制作U盘启动盘

Rufus官网地址：https://rufus.ie/zh/

下滑选择rufus-4. 6. exe版本进行下载

下载完成后，打开软件，插入一个空U盘

如图在软件中选择刚刚下载的Ubuntu镜像和刚刚插入的U盘

![images](https://github.com/luyu512/Windows-Ubuntu-dual-system-installation/blob/main/Screenshots/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE%202025-03-30%20210735.png)


![images](https://github.com/luyu512/Windows-Ubuntu-dual-system-installation/blob/main/Screenshots/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE%202025-03-30%20210819.png)

然后点击开始（此过程会格式化U盘，故务必提前备份好重要文件）

## 第三步：为Ubuntu系统预留磁盘空间

右键Windows徽标，选择磁盘管理

![images](https://github.com/luyu512/Windows-Ubuntu-dual-system-installation/blob/main/Screenshots/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE%202025-03-30%20210849.png)

进入后右击希望安装Ubuntu系统的盘符（此示例选择了本人电脑中的E盘），然后选择压缩卷，随后输入希望压缩的硬盘空间容量

![images](https://github.com/luyu512/Windows-Ubuntu-dual-system-installation/blob/main/Screenshots/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE%202025-03-30%20210948.png)

完成后即可看到如图所示内容

![images](https://github.com/luyu512/Windows-Ubuntu-dual-system-installation/blob/main/Screenshots/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE%202025-03-30%20211027.png)

ubuntu系统将会被安装在此未分配空间中

## 第四步：通过高级启动来使用UbuntuU盘启动

如图，进入系统 > 恢复
![images](https://github.com/luyu512/Windows-Ubuntu-dual-system-installation/blob/main/Screenshots/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE%202025-03-30%20211216.png)

向下翻，选择“高级启动”

此时电脑会重启，随后出现如下界面

![images](https://github.com/luyu512/Windows-Ubuntu-dual-system-installation/blob/main/Screenshots/_cgi-bin_mmwebwx-bin_webwxgetmsgimg__%26MsgID%3D4862885888848176931%26skey%3D%40crypt_bfda5cdf_4490b739b0db8f44bafe10ff62741be4%26mmweb_appid%3Dwx_webfilehelper.jpg)

选择“使用设备”

随后选择装有Ubuntu系统的U盘（每台电脑名称不一样，如有选错则重复第四步即可.........穷举法，小子！）
![images](https://github.com/luyu512/Windows-Ubuntu-dual-system-installation/blob/main/Screenshots/_cgi-bin_mmwebwx-bin_webwxgetmsgimg__%26MsgID%3D3472328889482667757%26skey%3D%40crypt_bfda5cdf_4490b739b0db8f44bafe10ff62741be4%26mmweb_appid%3Dwx_webfilehelper.jpg)

## 第五步，安装Ubuntu系统
如今Ubuntu安装界面已做的相当人性化，故在此不做过度赘述。

只有一点需要提示，安装位置建议选与Windows共存
![images](https://github.com/luyu512/Windows-Ubuntu-dual-system-installation/blob/main/Screenshots/3743e4a095c0405d958e5aa2a93bccfe.png)

![images](https://github.com/luyu512/Windows-Ubuntu-dual-system-installation/blob/main/Screenshots/c3c9592cb776431b818a3b894cfa3ad5.png)

![images](https://github.com/luyu512/Windows-Ubuntu-dual-system-installation/blob/main/Screenshots/274ee1defd6046ee9a262f5588d6b504.png)

## 最后三幅图图源：CSDN博主Return，在此鸣谢，侵权必删




