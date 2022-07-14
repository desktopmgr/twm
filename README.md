## twm  
  
### Tabbed window manager   
  
#### Requires scripts to be installed

```shell
sudo bash -c "$(curl -LSs <https://github.com/dfmgr/installer/raw/main/install.sh>)" && sudo dfmgr install installer
```

### Automatic install/update

```shell
dfmgr install twm
```

OR

```shell
bash -c "$(curl -LSs https://github.com/dfmgr/twm/raw/main/install.sh)"
```
  
requirements:
  
Debian based:

```shell
apt install twm
```  

Fedora Based:

```shell
yum install twm
```  

Arch Based:

```shell
pacman -S twm
```  

MacOS:  

```txt
Not supported
```
  
Manual install:  

  ```shell
APPDIR="$HOME/.local/share/CasjaysDev/dfmgr/twm"
mv -fv "$HOME/.config/twm" "$HOME/.config/twm.bak"
git clone https://github.com/dfmgr/twm "$APPDIR"
cp -Rfv "$APPDIR/etc/." "$HOME/.config/twm/"
[ -d "$APPDIR/bin" ] && cp -Rfv "$APPDIR/bin/." "$HOME/.local/bin/"
```
  
<p align=center>
   <a href="https://travis-ci.com/github/dfmgr/twm" target="_blank" rel="noopener noreferrer">
     <img src="https://travis-ci.com/dfmgr/twm.svg?branch=master" alt="Build Status"></a><br />
  <a href="https://wiki.archlinux.org/index.php/twm" target="_blank" rel="noopener noreferrer">twm wiki</a>  |  
  <a href="twm" target="_blank" rel="noopener noreferrer">twm site</a>
</p>  
