# robosyskadai2
# 2018ロボットシステム学課題２
# 概要
授業と同じことを5の倍数で行い，ブラウザで確認することができる．
# 手法
## 手順
授業資料と同じことを行う．
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
