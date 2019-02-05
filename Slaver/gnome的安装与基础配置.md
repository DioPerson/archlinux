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
退出。
更新一下。
sudo pacman -Syy
安装我们的密钥包
sudo pacman archlinuxcn-keyring
然后就可以安装网易云音乐，谷歌浏览器了
sudo pacman -S netease-cloud-music
sudo pacman -S google-chrome

安装第三方支持
sudo pacman -S yay yaourt

搜索 yay flat-remix
选择 gnome-git ---2
选择2.

在安装tilix
sudo pacman -S tilix

安装可选依赖
sudo pacman -S python-nautilus

配置Tilix
打开后选择左上角的下面下拉按钮——.>>选择Profiles——>>Edit Profile
选择Appearance——>>Theme variant ——>>Dark
选择Default——>>Color——>>Transparency  设置60%
选择Default——>>Color——>>Unfocused dim 设置60%

安装papirus
sudo pacman -S papirus-icon-theme
设置图标
打开Tweaks
需要安装主题
打开Extensions——>>User themes.
更改图标：Appearance——>>icons——>>选择
设置shell主题Appearance——>>Shell——>>选择
安装gtk的主题
搜索 yay vimix 
选择 vimix-gtk-theme -git 。
我这里是6.
