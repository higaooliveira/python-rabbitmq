# Python-rabbitmq
A simple example of using the Broker software architectural pattern with Python and Rabbit MQ

# **Setup**
- Download Rabbit MQ image from [Dockerhub](https://hub.docker.com/_/rabbitmq/ "Dockerhub")
- Run the command below on your terminal

`docker run --rm -p 5672:5672 -p 8080:15672 rabbitmq:3-management`

- Run this other command below on your terminal

`pip requirements.txt`

- Run the receiver.py file on your terminal so that the subscriber listens for the changes in the queue.
- Run the send.py file on your terminal to get the publisher to start publishing in the queue.
- Go back to the terminal on which you ran the file receiver.py
- See the Magic happen

[Tutorial Reference](https://blog.ateliedocodigo.com.br/primeiros-passos-com-rabbitmq-e-python-938fb0957019 "Tutorial Reference")
