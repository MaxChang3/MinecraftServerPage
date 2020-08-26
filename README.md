# MinecraftServerPage
English | [Chinese](https://github.com/xiaofan3p/MinecraftServerPage/blob/master/README_CN.md)

A django project help you show your minecraft server status based-on [mcstatus](https://github.com/Dinnerbone/mcstatus).
# Installation
Install python 3+ and clone this repo, and
```
pip install -r requirements.txt
```
then run the "START.BAT".  
you can see the pic in
```
http://{YOUR SERVER DOWMIANNAME}/stats.php?ip={YOUR IP ADDRESS}&title={YOUR SERVER NAME}&motd={A DESCRIPTION}
```
if your port is 25565, you needn't fill your port, example:  example.com  / exmaple.com:2333.
# Requirements
```
mcstatus==4.0.0
Django==3.0.6
Pillow==7.2.0
```
# Licence
Apache 2.0. 

[![avatar](https://camo.githubusercontent.com/a72e7743f15db219a6aba534f9de456e86268dd6/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f6c6963656e73652d416e74692532303939362d626c75652e7376673f7374796c653d666c61742d737175617265)](https://github.com/996icu/996.ICU/blob/master/LICENSE)
