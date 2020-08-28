## vifm  
  
vifm is a file manager with curses interface  
  
Automatic install/update:

```shell
bash -c "$(curl -LSs https://github.com/dfmgr/vifm/raw/master/install.sh)"
```

Manual install:
  
requires:

Debian based:

```shell
apt install vifm sxiv imagemagick
```  

Fedora Based:

```shell
yum install vifm sxiv imagemagick
```  

Arch Based:

```shell
pacman -S vifm sxiv imagemagick
```  

MacOS:  

```shell
brew install vifm sxiv imagemagick
```
  
```shell
mv -fv "$HOME/.config/vifm" "$HOME/.config/vifm.bak"
git clone https://github.com/dfmgr/vifm "$HOME/.config/vifm"
```
  
<p align=center>
  <a href="https://wiki.archlinux.org/index.php/vifm" target="_blank" rel="noopener noreferrer">vifm wiki</a>  |  
  <a href="https://vifm.info" target="_blank" rel="noopener noreferrer">vifm site</a>
</p>  
