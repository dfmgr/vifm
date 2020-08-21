## vifm  
  
vifm is a file manager with curses interface  
  
requires:    
apt: ```apt install vifm sxiv imagemagick```  
yum: ```yum install vifm sxiv ImageMagick```  
pacman: ```pacman -S vifm sxiv imagemagick```  
  
Automatic install/update:
```
bash -c "$(curl -LSs https://github.com/dfmgr/vifm/raw/master/install.sh)"
```
Manual install:
```
mv -fv "$HOME/.config/vifm" "$HOME/.config/vifm.bak"
git clone https://github.com/dfmgr/vifm "$HOME/.config/vifm"
```
  
  
<p align=center>
  <a href="https://wiki.archlinux.org/index.php/vifm" target="_blank">vifm wiki</a>  |  
  <a href="https://vifm.info/" target="_blank">vifm site</a>
</p>  
