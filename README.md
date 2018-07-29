Liquor detection using YOLO in AWS Ubuntu Deep learning AMI

1. Preparing dataset by Yolo_mark in your local PC

 1.1 Install Yolo_mark
  git clone https://github.com/AlexeyAB/Yolo_mark
  cmake .
  make
  ./linux_mark.sh
  reference : https://github.com/AlexeyAB/Yolo_mark

 1.2 Download liquor image from google using googliser library.
  git clone https://github.com/teracow/googliser
  ./googliser <command>
  reference : https://github.com/teracow/googliser

 1.3 Delete unnecessary images by manual before make label

