gnome桌面的安装
安装xorg服务
pacman -S xorg
安装gnome桌面
pacman -S gnome
intel cpu：
安装—— pacman -S intel-ucode
gnome 额外的包：
pacman -S gnome-extra
登录管理器：
systemctl enable gdm
网络管理：
systemctl enable NetworkManager
添加一个用户
useradd -m -G wheel -s /bin/zsh slaver
安装zsh
pacman -S zsh

设置普通用户提权操作
vim /etc/sudoers
大概82行
将 %wheel ALL=(ALL) NOPASSDW :ALL 取消注释
然后退出
安装中文字体
pacman -S wqy-zenhei
安装浏览器
pacman -S firefox

设置用户密码：
passwd slaver

重启：
reboot
然后输入密码：，在点击设置选择Xorg.然后登录。

gnome桌面的基础配置

打开Terminal应用
安装 
sudo pacman -S gnome-tweaks

打开Tweaks 进行一些简单的配置
windowsTitlebars 的minmize设置

打开浏览器 搜索ohmyz.sh.
copy 链接

安装git
sudo pacman -S git

编辑 zshrc
vim .zshrc
设置为ZSH_THEME="ys"
把 plugins=(git) 设置为 plugins=(git  sudo) 
退出
生效配置文件
source .zshrc
打开百度搜索 ：ustc archlinuxcn.
选择第一个网站
复制使用方法的两行的内容

sudo vim /etc/pacman.conf
把Color取消注释
把TotalDownload 取消注释
把VerbosePkgLists 取消注释
打开32的仓库
multilib里的内容取消注释。
加入我们archlinux的源
刚刚我们复制的内容，在最后一行粘贴。按ctrl+Shift+ins
