# DDoS-demo

A demo of C/S model botnet structure and SYN attack. 

# Brief Introduction

The Flask API server is attacker, the client python program is bot.

Server initiates attacking packets, and bots poll the server's state and act.

# Quick Start

```shell script
git clone https://github.com/ESWZY/DDoS-demo.git
cd DDoS-demo
pip install -r requirements.txt
cd server
python server.py
```

In `victim.txt`, change the `host` and `port` to yours. And then open another console here.

```shell script
cd ..
cd client
python main.py
```

# Result

API request result:

![api](/images/1.png)

DoS result:

![dos](/images/2.png)

