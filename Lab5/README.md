## Lab 5

After installing Mosquitto and Paho on both my Windows Machine and my RaspberryPi using the follow commands, I updated the iot repository

```
pacman -S mingw-w64-clang-x86_64-paho.mqtt.c
```
and

```
sudo pip3 install -U paho-mqtt
```

![1]()

Then running the follow command on my windows device
```
python3 subcpu.py
```

and the following on my RaspberryPi

```
python3 pubcpu.py
```

I was able to get the CPU usage readings from one device to the other as shown

![2](https://github.com/jgoceljak/CPE-322-A/blob/bd8342acb7bfd3147c7a72fea113ec9e57914693/Lab5/cpuusage.jpg)
