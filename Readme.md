<h1 align="center">
  Hi 👋, Welcome to ChatSSH Project 
</h1>
<h2>About the Project</h2>
<h3>
this it the final practical homework of principles of security 
</h3>
<h4>the aim of the project is to have a chatroom in which users can login into the server via ssh connection </h4>
<h4>due to ssh encrypted tunnel connection the whole messages are encrypted</h4>
<h5>the instruction how to run chatSSH </h5>


```shell
python3 -m venv venv
source venv/bin/activate
pip3 install -r requirements.txt
```

<h3> Running ChatServer </h3>
<h4> you have to pass host and port to run Server </h4>

````python
python3 chatServer.py 127.0.0.1 9000
````


<h3> Running Client </h3>
<h4> you have to pass host and port to run client side  </h4>

```python
python3 chatClient.py 127.0.0.1 9000
```

here , there are some screenshots of running a demo 
<h4>running server </h4>
<img src="https://github.com/amirhasance/chat_ssh/raw/main/img/runningServer.png" >

<h4>client_1 'amir' ssh to server </h4>
<img src="https://github.com/amirhasance/chat_ssh/raw/main/img/client_1_Amir.png" >


<h4>two clients are chatting </h4>
<img src="https://github.com/amirhasance/chat_ssh/raw/main/img/Screenshot%202023-01-25%20at%2021.52.47.png">

<h4>chat server is rendering the room</h4>
<img src="https://github.com/amirhasance/chat_ssh/raw/main/img/server_rendering_chats.png">
