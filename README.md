<div align="right"><img src="https://raw.githubusercontent.com/jusdepatate/info.sh/master/logomadein5minutes.png" /></div><br>

<a href="https://github.com/jusdepatate/info.sh/blob/master/info.sh"><i>info.sh</i></a> is a little script that works like `screenfetch` or `neofetch` it shows infos and was originally made for Termux (Linux on Android) but it was tested on Ubuntu and Termux (with zsh for all of them)

## Works on
Ubuntu (tested with official Ubuntu and WSL), Termux, Debian (tested with 9.x), [iSH](https://ish.app), [Windows 10](https://github.com/jusdepatate/info.sh/blob/master/info.bat)

## Doesn't works on
### Partially works
Arch Linux (thanks to oräkle), GhostBSD
### Shows nothing
...

## Features
- Shows IP (public and local)
- Shows OS and version (only on Ubuntu and Android)
- Shows username and hostname
- Bad code
- Shows Mobile ISP (only on Termux)

### Planned
- [~~Show IPv4 and IPv6 on two different line~~](https://github.com/jusdepatate/info.sh/commit/c2a929935705e8647f2cce32a9d5e4fc54d026a6)
- [~~Explain every line~~](https://github.com/jusdepatate/info.sh/commit/f45db7cf90e5f412541e4a05098dfabed694d5d0)
- [~~Compatibility with iSH~~](https://github.com/jusdepatate/info.sh/commit/f3bbc05b6e4225d06757b54f31ecff7ef60b2448)
- [~~.bat version~~](https://github.com/jusdepatate/info.sh/commit/429e13447603005a4631155ed11b436d3561e29e)
- Compatibility with MAC OS
- Compatibility with \*BSD

## Example :

From WSL
```
xen@DESKTOP-GKG4PAL
Ubuntu Xenial 16.04 (Linux 4.4.0-17134-Microsoft)
Package Arch: amd64
Shell: zsh 5.1.1
Public IP: REDACTED (FR)
Local IP: 192.168.0.15


Report any errors here :
https://github.com/jusdepatate/info.sh
```

From Termux
```
u0_a314@HUAWEI WAS-LX1A
Android 8.0.0 (Linux 4.4.23+)
Package Arch: aarch64
Shell: zsh 5.6.2
Public IP: REDACTED (FR)
Local IP: 192.168.0.19
Mobile ISP : Free (fr)

Report any errors here :
https://github.com/jusdepatate/info.sh
```

From iSH
```
root@jdpiPad                                                                                                                              
iOS/Alpine Linux (Linux 3.2.0-ish)                                                                                                         
Arch: i686                                                                                                                                 
Shell: ash                                                                                                                                 
Public IP(v4): REDACTED (FR)                                                                                                         
You probably have an IPv6 but iSH doesn't support it :(                                                                                    
Due to limitation of iSH this script is unable to show local ip                                                                            
                                                                                                                                           
Report any errors here :                                                                                                                   
https://github.com/jusdepatate/info.sh    
```

From Debian
```
jusdepatate@jdpVPS
Debian GNU/Linux 9 (stretch) (Linux 4.9.0-8-amd64)
Package Arch: amd64
Shell: zsh 5.3.1
Public IP(v4): 185.216.25.100 (FR)
Local IP: 185.216.25.1


Report any errors here :
https://github.com/jusdepatate/info.sh
```

From Windows
```
jusdepatate@DESKTOP-GKG4PAL
Microsoft Windows 10 (Windows NT 10.0)
Arch: AMD64
CMD: cmd.exe
Public IP(v4): REDACTED (FR)
Public IP(v6): REDACTED (FR)
Local IP: 192.168.0.18

Report any errors here :
https://github.com/jusdepatate/info.sh
```

Pull requests and issues are welcome :)<br>
<img width="80px" src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/0a/By-nc.svg/2560px-By-nc.svg">
