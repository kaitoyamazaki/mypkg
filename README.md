# mypkg

# 概要
ロボットシステム学の課題2で作ったものです。
ROSのturtlesimにより亀を描画し、回転させ続けるものを作成しました。

# 実行環境

以下の環境で行っています。

・ROS Melodic

・Ubuntu 18.04LTS


# 環境構築
## 1.本パッケージのインストール
    $ `cd ~/catkin_ws/src`
    $ `git clone https://github.com/kaitoyamazaki/mypkg.git`
    $ `cd ~/catkin_ws`
    $ `catkin_make`
    
## 2.turtlesimのインストール
    $ `sudo apt-get install ros-melodic-ros-tutorials`
    
    
# 実行方法

## 1.ROSを立ち上げる。
    $ `roscore &`

## 2.実行できるようにkame.pyのパーミッション設定を行う。
    $ `cd ~/catkin_ws/src/mypkg/scripts`
    $ `chmod +x kame.py`
    
## 3.ノードを実行する
    $ `rosrun turtlesim turtlesim_node`
    $ `rosrun mypkg kame.py`
    
    
# 映像


# LICENSE

BSD 3-Clause "New"or"Revised" License

# References
https://ryuichiueda.github.io/robosys2020/lesson10_ros.html#/

参考にしたロボットシステム学の講義資料です。

https://symfoware.blog.fc2.com/blog-entry-2283.html
http://wiki.ros.org/turtlesim/Tutorials/Moving%20in%20a%20Straight%20Line#CA-e22c413483c3a71f8104cdebb87bfe28a08bcf54_5

ROSでturtlesimを使用する際に参考にしたページです。
