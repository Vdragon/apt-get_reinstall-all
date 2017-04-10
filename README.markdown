# apt-get reinstall-all
A script to reinstall all packages installed in system  
<https://github.com/Vdragon/apt-get_reinstall-all>

## 這是什麼？<br />What is this?
這是讓重新安裝 APT 目前已經安裝的所有軟體包的程式

## 軟體下載<br />Software download
您可以下載釋出的軟體於  
You may download software releases at  
[https://github.com/Vdragon/apt-get_reinstall-all/releases](https://github.com/Vdragon/apt-get_reinstall-all/releases)

## 軟體依賴關係<br />Software dependency
* GNU Bash 殼程式  
  GNU Bash shell
* APT 軟體包管理系統  
  APT software package management system

## 如何安裝？<br />How to install?
在終端機內於專案根目錄下以 root 身份執行 `make install` 即可安裝  
Just run `make install` command as root in the terminal in the project's root directory to install apt-get_reinstall-all

## 如何移除軟體？<br />How to remove software?
在終端機內於專案根目錄下以 root 身份執行 `make uninstall` 即可移除 apt-get reinstall-all  
Just run `make uninstall` command as root in the terminal in the project's root directory to remove apt-get reinstall-all

## 命令語法<br />Command syntax
`# apt-get_reinstall-all`

`$ sudo apt-get_reinstall-all`

## 感謝<br />Credits
本專案的程式雛型來自下列由 [
Lumenary](http://ubuntuforums.org/member.php?u=534275) 所發表的文章：  
This project's program prototype came from the article published by [
Lumenary](http://ubuntuforums.org/member.php?u=534275):  
[Advanced: Reinstall (Almost) All Packages Without Reinstalling All Of Ubuntu](http://ubuntuforums.org/showthread.php?t=735693)

其作法基於 Tod Detre 於 [debianHELP.org](http://www.debianhelp.org/) 上提供的[解決方案](http://www.debianhelp.org/node/10487)。  
Which method is based on the [solution](http://www.debianhelp.org/node/10487) presented by Tod Detre on [debianHELP.org](http://www.debianhelp.org/).

## 作者<br />Authors
[Ｖ字龍(Vdragon)](mailto:pika1021@gmail.com)與本專案其他貢獻者

## 授權條款<br />License
GPL 3.0 或是其更近期的任一版本