# kaliNethuter - termux
## system requirment
* Androide device (rootless) 
* Termux app
* 8GB storage

### Installation of termux:
* link :- https://play.google.com/store/apps/details?id=com.termux&hl=en_IN&gl=US
 
 ### Installing the kali-nethunter 
 * kali@kali:~$ termux-setup-storage
 * kali@kali:~$ pkg install wget
* kali@kali:~$ wget -O install-nethunter-termux https://offs.ec/2MceZWr
* kali@kali:~$ chmod +x install-nethunter-termux
* kali@kali:~$ ./install-nethunter-termux

**once the installations is over:**
* Enter the **ls** command in your termux

>if you see the  kalifs-arm64-full.tar.xz ,kali-arm and install-nethunter-termux  and storage 

* **if you see kalifs-arm64-full.tar.st and kalifs-arm64-full.tar.xz.0 ,kalifs-arm64-full.tar.xz.1 remove these file**

* **rm kalifs-arm64-full.tar.st , rm kalifs-arm64-full.tar.xz.0 and rm kalifs-arm64-full.tar.xz.1**

* Now re Run the installer by typing **./install-nethunter-termux** ,it will say **"Existing rootfs found,delete and download new one (Y/n)?", type n and click enter.**

* It will show "extracting rootfs file",that means Kali-Nethunter is being installed.

> This will take from 10to 20min,so make sure you have enough battery in your phone.

> The **KALI** image you will see at front ,thats it.

> Now you can goto the kali web_site link :- https://www.kali.org/docs/nethunter/nethunter-rootless/ to see how to start the nethunter etc.

* To access the GUI version,you need Nethunter Kex app, download it from Nethunter-App store from store.nethunter.com

