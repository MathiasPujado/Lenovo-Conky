 
### Lenovo-conky :computer: 
 
This is a complete [conky](https://github.com/brndnmtthws/conky) config for my Lenovo Notebook. 
I'm using `Debian 9 Stretch with KDE Plasma 5.8.6`. 
 
<img src="https://github.com/MathiasPujado/Lenovo-conky/blob/master/Conkyrc01_fixed.jpg" id=presentation1> 
 
--- 
 
* [Compatibility](#compatibility) 
* [Installation](#installation) 
* [Configuration](#configuration) 
 
--- 
 
### Compatibility: 
 
The latest version of this theme is on the master branch, and it supports conky `1.10.x`. 
 
--- 
 
### Installation: 
 
* Install **conky**, **curl**, **net-tools**, **lmsensors** and **Optimus nvidia-propietary drivers**. 
 
* Make sure you have the **Comfortaa** font installed. `(You may use any other font you like)' 
 
* In the **home directory** create a file named `.conky` and put inside `Debian9` folder and the three conkyrc files `(conkyrc_tr, conkyrc_tm and conkyrc_tl)`. 
 
* Make sure **ip.sh** inside **Debian9** folder is executable. If not, type in the terminal `chmod x+ ip.sh`. 
 
--- 
 
### Configuration: 
 
* `conkyrc_tr`: You might want to change the System info and the address of the partitions you care about. In this example I have a second HDD with two partitions. 
 
* `conkyrc_tm`: You can run it as is, and might modify it to show seconds or calendar. 
 
* `conkyrc_tl`: You may change the data of the graphic card in order to display correctly the info you need. In case the network section doesn't display correctly, you need to find the name of your network interface and change it. 
 
 
> **NOTE:**   
> Replace `enp1s0` string for Ethernet and `wlp2s0` string for Wifi. 
 
 
Hope you enjoy it. :smile: 

 ---
 
### `conkyrc_tl`

<img width="230" height="550" src="https://github.com/MathiasPujado/Lenovo-conky/blob/master/Conkyrc02_tr.jpg" id=conkyrc_tr> 

### `conkyrc_tm`
<img width="150" height="100" src="https://github.com/MathiasPujado/Lenovo-conky/blob/master/Conkyrc02_tm.jpg" id=conkyrc_tm>

### `conkyrc_tr`
<img width="230" height="550" src="https://github.com/MathiasPujado/Lenovo-conky/blob/master/Conkyrc02_tl.jpg" id=conkyrc_tl> 

 
 
