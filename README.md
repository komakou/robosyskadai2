# robosyskadai2
# 2018ロボットシステム学課題２
# 概要
授業と同じことを5の倍数で行い，ブラウザで確認することができます．
# 手法
## 手順
授業資料と同じことを行う．以下を参考に行っています．
https://github.com/ryuichiueda/robosys2018/blob/master/11.md
https://github.com/ryuichiueda/robosys2018/blob/master/13.md
```
$ roscore
$ rosrun mypkg count.py　
$ rosrun mypkg twice.py
```
プログラムを動かす際にtmuxを使用しています．
```
$ sudo apt install tmux
```
## 実行
```
$ roslaunch mypkg mypkg.launch 
```
http://ラズパイのIPアドレス:8000で見ることが可能
## youtube
ロボシス課題２
https://youtu.be/T8DETCCRXIQ
