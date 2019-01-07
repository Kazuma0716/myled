# myled
ロボットシステム学課題  
LEDを点灯させるデバイスドライバ  
GPIO25を使用  

# 実行方法
```bash
$ git clone https://github.com/Kazuma0716/myled.git
$ cd myled
$ make
$ sudo insmod myled.ko
$ sudo chmod 666 /dev/myled0
###点灯###
$ echo 1 > /dev/myled0
###消灯###
$ echo 0 > /dev/myled0
```
