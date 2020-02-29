# EXAMPLES--RabbitMQ

### Quick start 
1. Install Erlang for RMQ - [Link](https://www.erlang.org/downloads)
2. Install RabbitMQ service - [Link](https://www.rabbitmq.com/install-windows.html#installer)
3. Start `writer.js` - after output, close console
4. Start `receive.js` - receive message from RMQ service

### Check queues and messages there
###### unix
```sh
sudo rabbitmqctl list_queues
```

###### windows 
```sh
# (rabbitmq_server/sbin/rabbitmqctl.bat)
rabbitmqctl.bat list_queues
```
