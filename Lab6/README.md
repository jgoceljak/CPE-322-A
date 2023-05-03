## Lab 6

To run the first example for lab 6, I navigated to the lesson 6 folder and ran the following command.
```
node hello-world.js
```

Then going to the browser, I opened the address 127.0.0.1:3000 and this was the output

![1]()

For the second example I had to change a part of the code in the http.js file, namely the listen(8080) near the end of the file to listen(3000) so it would go to the same address

```
.listen(3000);
```
Then upon running the following command for the example, this was the result

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
