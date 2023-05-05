## Lab 8


First I ran the following commands on my Pi to download all the necessary libraries

```
$ sudo apt update
$ sudo apt install python3-scipy
$ sudo apt install python3-matplotlib
$ sudo apt install python3-pandas
$ sudo apt install libopenblas-dev
$ sudo apt install libatlas-base-dev
$ sudo pip3 install -U numpy
$ sudo pip3 install --only-binary :all: -U scikit-learn
$ sudo pip3 install -U tensorflow
$ sudo pip3 install -U keras==2.3.1
```

After this, I ran some of the sample code using the libraries

![1]()

![2]()

![3]()

Then I downloaded the sheet from lab 7 as a csv file onto my pi, and edited plt_final.py and plt_cv2.py to refer to the correct file name.

Then I ran plt_cv2.py

![4]()
