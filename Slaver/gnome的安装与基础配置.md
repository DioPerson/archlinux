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