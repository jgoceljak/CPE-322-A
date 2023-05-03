## Lab 6

To run the first example for lab 6, I navigated to the lesson 6 folder and ran the following command.
```
node hello-world.js
```

Then going to the browser, I opened the address 127.0.0.1:3000 and this was the output

![1](https://github.com/jgoceljak/CPE-322-A/blob/3fa18c5059b906fd4df430225b678d8deacd67c3/Lab6/nodejs%20output.jpg)

For the second example I had to change a part of the code in the http.js file, namely the listen(8080) near the end of the file to listen(3000) so it would go to the same address

```
.listen(3000);
```
Then upon running the following command for the example, this was the result. The terminal updates with the amount of times the page was refreshed by the user.

```
node http.js
```

![2]()

For the next part of the lab, I had to install pysstache onto my windows device using the following command.

```
pip install pystache
```

Once this was completed, I ran the following command

```
python3 say_hello.py
```

and achieved this output

![3]()
