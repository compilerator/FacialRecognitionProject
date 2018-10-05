Commands to be issued:
=======================
 (C) 2018 Shayantan , Prateek 

source ~/.profile 
workon cv
cd /home/pi/FacialRecognitionProject
sudo modprobe bcm2835-v4l2

Edit 01.py for face_id number change
python 01.py
python 02_face_training.py
python 03_face_recognition.py