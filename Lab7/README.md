## Lab 7

First I logged into Thingspeak using my stevens account, and then created a new channel cpu_loop with field1 cpu_pc and field2 mem_avail_mb

Using the following commands, I created a demo folder and copied two thingspeak files into it. 

```
sudo pip3 install -U psutil
cd ~/demo
cp ~/iot/lesson7/thingspeak_cpu_loop.py .
cp ~/iot/lesson7/thingspeak_feed.py .
cat thingspeak_cpu_loop.py
cat thingspeak_feed.py
python3 thingspeak_feed.py
```

When prompted to enter my API key, I entered the key provided for the channel on Thingspeak

After running thingspeak_feed.py for a couple minutes, I got the following output on the website

![1](https://github.com/jgoceljak/CPE-322-A/blob/1ab24ac791b223f12258bb66a40c16af5ffaf0f9/Lab7/websiteresults.jpg)

For the second part of the lab, I went to the Google Cloud Platform Identity and Access Management site and created a new project rpidata. From there I enabled drive and sheets API, and created a service account. With this service account, I created a json file and downloaded it. 

![2](https://github.com/jgoceljak/CPE-322-A/blob/49179cee7fcb82345d5b30ae276e07d0f0f88b57/Lab7/json.jpg)

Using the following command, I installed gspread and oauth2client onto my Pi

```
sudo pip3 install -U gspread oauth2client
```

I then copied system_info.py, rpi_spreadsheet.py, and the json key file into the same demo folder from the first part, and edited the file to have the json key file name. 

Then after running program, the spreadsheet was gradually populated with the following data.

![3]()
