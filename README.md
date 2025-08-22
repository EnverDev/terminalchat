# Terminal Chat

## Tiny terminal chat with an asyncio server and CLI client. Python 3.12+.

## Install (local dev)
```
pip install -e .
```

## Run the server
```
terminalchat-server --host 0.0.0.0 --port 9000
```

## Connect a client
```
terminalchat 127.0.0.1 9000 --name alice

# In another 

terminal
terminalchat 127.0.0.1 9000 --name bob
```

Type to chat. Commands:

* /nick <name> change nickname
* /quit leave
