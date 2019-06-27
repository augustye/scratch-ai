# scratch-ai

Required Python 3 packages
-------------------------
 - tensorflow 1.x
 - opencv 3.x
 - pygame 
 - flask 
 - Pillow

If you use Raspberry Pi, you can follow the instructions in [install/raspberry_pi.sh](https://github.com/augustye/scratch-ai/blob/master/install/raspberry_pi.sh)

If you use Jetson Nano, you can follow the instructions in [install/jetson_nano.sh](https://github.com/augustye/scratch-ai/blob/master/install/jetson_nano.sh)


Start python server
-------------------
Run this in console:
```Bash
git clone https://github.com/augustye/scratch-ai
cd scratch-ai
python3 server.py
```
If you use a console-only system without X window, you need to run the commands with root to see the display

Run Scratch 3.0 in Browser:
---------------------------
1. open scratch: http://scratch.augustye.net/?url=http://192.168.3.103:8888/extension/mnist
   - replace 192.168.3.103 with the ip address of your python server
   - you can open the link on PC or iPad
2. you will find the "MINST" block on the left side
3. download scratch project: https://github.com/augustye/scratch-ai/raw/master/static/draw.sb3
4. open the downloaded project 
