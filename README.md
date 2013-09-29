Chatroom
===========

chatroom is a chat app of Uliweb. So it'll be used in Uliweb application. And
this project shipped with some example projects, so you can run and test it.

## Installation

Make sure you've already istalled the lastest version of Uliweb.

```
pip install gevent-socketio
```

## How to test

```
cd chatroom/examples/simple
uliweb runserver --gevent-socketio or python gevent_socketio_handler.py
```

Visit: http://localhost:8000 (the former) or http://localhost (the later)