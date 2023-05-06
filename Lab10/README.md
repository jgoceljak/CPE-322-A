## Lab 10

First ran hash_value.py inside the iot/lesson10 folder twice to compare the results

```
python3 hash_value.py
python3 hash_value.py
```

![1]()

Then installed the hashlib in python3 in order to see the digest and block sizes of this specific hash algorithm

![2]()

Then by running snakecoin.py, created a 20 block block chain

![3]()

Then using two seperate terminals on my Pi, on the first terminal I ran the snakecoin server locally, and on the second terminal I created a transation and mined a new block

First Terminal Commands
```
$ cat snakecoin-server-full-code.py
$ python3 snakecoin-server-full-code.py
```

Second Terminal Commands
```
$ curl "localhost:5000/txion" \
     -H "Content-Type: application/json" \
     -d '{"from": "akjflw", "to":"fjlakdj", "amount": 3}'
$ curl localhost:5000/mine
```
![4]()

For the next part, for some reason I didn't have access to cloning the repository, so I just manually downloaded the zip and extracted it.

On the same first terminal as before, I ran the following commands and changed the last line of the file to be uncommented.
```
$ git clone https://github.com/satwikkansal/python_blockchain_app.git
$ cd ~/python_blockchain_app
$ nano node_server.py
$ python3 node_server.py
```

Then on the second terminal, I ran the following to run Yournet
```
$ vncserver
$ cd ~/python_blockchain_app
$ python3 run_app.py
```

![5]()

![6]()

![7]()



