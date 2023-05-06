## Lab 9

First I installed Pyang by running the following two commands

```
$ sudo apt install libxml2-dev libxslt1-dev
$ sudo pip3 install -U lxml pyang
```

Since my only demo folder was in lesson7, I made a new demo folder for this lab. I navigated to this new demo folder, then ran Pyang using the following commands. 

```
cat intrusiondetection.yang
$ pyang -f yin -o intrusiondetection.yin intrusiondetection.yang
$ cat intrusiondetection.yin
$ pyang -f uml -o intrusiondetection.uml intrusiondetection.yang --uml-no=stereotypes,annotation,typedef
$ cat intrusiondetection.uml
```

![1](https://github.com/jgoceljak/CPE-322-A/blob/470c6e8540e2fc540a8651553207aae1fcdb4463/Lab9/IMG_2735.JPG)

Once pyang was run, I installed plantUML and ran it to create the sequence diagram in PNG

```
sudo pip3 install -U plantuml
python3 -m plantuml intrusiondetection.uml
```

To install GIMP, I ran the following command:

```
sudo apt install gimp pinta
```

Then inside the demo folder, I ran the following two gimp commands to open gimp and display the sequence diagram in the program

```
gimp -h
gimp -a intrusiondetection.png
```

![2]()
