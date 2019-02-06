**ArchLinux在安装VMware Workstation Pro15.0.2 虚拟机上安装**
我先说明：我自己也是个超级菜鸡，我自己喜欢的东西就是去弄它，我自己先是看了官方的wiki,
英文嘛，我不说了，那是什么东西，翻译了一下看的时候，还是不太看的懂，没办法小白就是这样。我然后就去网上找其他教程，第一个找到的是图文版教程，我还是不太懂怎么操作。就科学上网，谷歌了一下。找到了youtobe视频，我那时发现只有一个不好的地方，那是语言障碍，他们说的太快，翻译没有那么快，我就先放弃了，我到了现在找到了方法看youtobe（youtobe翻译中文）不怕翻译跟不了，我在bilibili网站看到linux的安装教程，我这是还是看到我同学才知道原来bilibili网站还可以这么玩。通过up主的视频成功第一次安装上基本版的Archlinux发行版。我这次时up主视频安装图文版教我的方式。我往后就去学习bilibili网站的up主的方式安装。之中我有好多次重新新建系统。没有办，错了一步，我就不会怎么解决了。我唯一疑惑的是那个分区的问题。我最后跟了一个UP主安装gnome桌面。就这样。不好意思我说废话了。
# 去官方下载好Arch Linux的镜像文件：[archlinux.org](https://www.archlinux.org)

![ArchLinux下载网页](https://img-blog.csdnimg.cn/20181225195710588.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQxMjk4Njc1,size_16,color_FFFFFF,t_70)

选择 download ，它有几种方式下载。
我选择的是磁力下载，单击磁铁图标，迅雷就会可以下载了
[VMware Workstation Pro15.0.2下载](https://www.vmware.com/go/getworkstation-win)
)也可以通过迅雷一并下载。
虚拟机安装就不用我说了吧，很简单 ，注册密钥网上很多。
**激活密钥：**

ZC10K-8EF57-084QZ-VXYXE-ZF2XF

UF71K-2TW5J-M88QZ-8WMNT-WKUY4

AZ7MK-44Y1J-H819Z-WMYNC-N7ATF

CU702-DRD1M-H89GP-JFW5E-YL8X6

YY5EA-00XDJ-480RP-35QQV-XY8F6

VA510-23F57-M85PY-7FN7C-MCRG0

**创建与启动前的设置**
新建——>>输入名字archlinux  选择下载好的ios文件——>>下一步系统类型选择Linux,版本选择其他LInux4.x 64位——>>下一步选择虚拟机的名称和位置——>>下一步选择硬盘大小我这里选择的32.1GB，100M——>>是EFI需要的大小——>>自定义硬盘设置----->>我把处理器设为4，你们随根据自己的电脑设置，内存大小的设置，选项的高级，设置引导——>>完成。

![在这里插入图片描述](https://img-blog.csdnimg.cn/20181225211328393.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQxMjk4Njc1,size_16,color_FFFFFF,t_70)
![在这里插入图片描述](https://img-blog.csdnimg.cn/20181225211355729.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQxMjk4Njc1,size_16,color_FFFFFF,t_70)
![在这里插入图片描述](https://img-blog.csdnimg.cn/20181225211412962.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQxMjk4Njc1,size_16,color_FFFFFF,t_70)
![在这里插入图片描述](https://img-blog.csdnimg.cn/20181225211433329.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQxMjk4Njc1,size_16,color_FFFFFF,t_70)
![在这里插入图片描述](https://img-blog.csdnimg.cn/20181225211445962.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQxMjk4Njc1,size_16,color_FFFFFF,t_70)
![在这里插入图片描述](https://img-blog.csdnimg.cn/20181225211550824.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQxMjk4Njc1,size_16,color_FFFFFF,t_70)
![在这里插入图片描述](https://img-blog.csdnimg.cn/2018122521211085.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQxMjk4Njc1,size_16,color_FFFFFF,t_70)


## 基础安装
![在这里插入图片描述](https://img-blog.csdnimg.cn/20181225202718732.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQxMjk4Njc1,size_16,color_FFFFFF,t_70)
我们这里选择第一个64位安装模式



## 按<kbd>Enetr</kbd>键，等着开机启动即可

![在这里插入图片描述](https://img-blog.csdnimg.cn/20181225212723736.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQxMjk4Njc1,size_16,color_FFFFFF,t_70)

`参考Wiki`
**1.验证引导模式**
 `ls /sys/firmware/efi/efivars`
![在这里插入图片描述](https://img-blog.csdnimg.cn/20181225220028186.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQxMjk4Njc1,size_16,color_FFFFFF,t_70)
有输出信息说明就是了。

**2.测试网络的连通性**

`ping -c 4 baidu.com`
![在这里插入图片描述](https://img-blog.csdnimg.cn/20181225220519845.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQxMjk4Njc1,size_16,color_FFFFFF,t_70)
还有wifi-menu命令 我没有用过，你自己试试吧

**2.更新系统时钟**

`timedatectl set-ntp true`

**3.分区磁盘**
`fdisk`
**3.磁盘查看**

`fdisk -l`
![在这里插入图片描述](https://img-blog.csdnimg.cn/20181225220849842.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQxMjk4Njc1,size_16,color_FFFFFF,t_70)



**4.磁盘分区**

`cfdisk /dev/sda`
选择gdp
![在这里插入图片描述](https://img-blog.csdnimg.cn/20181225221725454.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQxMjk4Njc1,size_16,color_FFFFFF,t_70)
==第三个分区需要换成EFI system类型==
write写入硬盘
输入yes确认
quit退出

`fdisk -l`查看刚刚磁盘分区信息：
**5.格式化分区.***

`mkfs.ext4 /dev/sda1`

`mkfs.ext4 /dev/sda2`

`mkfs.vfat /dev/sda3`

![在这里插入图片描述](https://img-blog.csdnimg.cn/20181225223945909.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQxMjk4Njc1,size_16,color_FFFFFF,t_70)

**6.挂载文件系统.**

`mount /dev/sda1 /mnt`

`mkdir /mnt/home`

`mkdir -p /mnt/boot/efi`

`mount /dev/sda2 /mnt/home`

`mount /dev/sda3 /mnt/boot/efi`

![在这里插入图片描述](https://img-blog.csdnimg.cn/20181225223956844.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQxMjk4Njc1,size_16,color_FFFFFF,t_70)
**7.更换下载系统的源**

`vim /etc/pacman.d/mirrorlist`

将第一个地址换清华大学的源：Server = https://mirrors.tuna.tsinghua.edu.cn/archlinux/$repo/os/$arch
这样方便下载。


按<kbd>esc</kbd>键输入“:wq”<kbd>Enter</kbd>
更新软件包缓存：` pacman -Syy`

**8.下载安装系统**
` pacstrap -i  /mnt base base-devel `

一路按<kbd>Enter</kbd>键 代表默认安装

![在这里插入图片描述](https://img-blog.csdnimg.cn/20181225225722125.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQxMjk4Njc1,size_16,color_FFFFFF,t_70)
**9.生成一个 fstab 文件来规定磁盘分区、块设备，或者远程文件系统是如何挂载进文件系统中：**

` genfstab -U /mnt >>/mnt/etc/fstab`

**10.进入 chroot 环境，这样可以为当前进程以及子进程切换当前根目录：**

`arch-chroot/mnt`

有没有观察到root变色了？说明成功进入chroot环境
我安装一个vim 方便我下一步操作


设置编码
` vim /etc/locale.gen`

![在这里插入图片描述](https://img-blog.csdnimg.cn/20181225230901802.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQxMjk4Njc1,size_16,color_FFFFFF,t_70)
![> 引用文本](https://img-blog.csdnimg.cn/20181225230936427.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQxMjk4Njc1,size_16,color_FFFFFF,t_70)

中文和英文的utf-8
保存退出 :wq  

locale-gen

echo LANG=en_US.UTF-8 > /etc/locale.conf


设置系统主机名：

echo "arch-dww" > /etc/hostname

设置系统时区和时钟信息
ln -sf /usr/share/zoneinfo/Asia/Shanghai /etc/localtime

生成一个 efibootmgr 文件来规定磁盘分区、块设备，或者远程文件系统是如何挂载进文件系统中：
pacman -S grub efibootmgr
 boot:pacman -S
 
grub-install --target=x86_64-efi --efi-directory=/boot/efi --bootloader-id=ArchLinux

boot+grub:
grub-install --target=i386-pc /dev/sda

生成配置文件
grub-mkconfig -o /boot/grub/grub.cfg

设置自动联网:
systemctl enable dhcpcd

笔记本需要安装：
pacman -Ss wpa_supplicant
pacman -Ss wpa_supplicant dialog

退出：
exit

卸载硬盘分区：
umount -R /mnt

重启：
reboot

root用户密码：
passwd root
然后输入两次密码。

uname -a

cat /etc/os_release

ping baidu.com





