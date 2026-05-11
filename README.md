# Module 9 - Software Architecture (Subscriber)


1. What is amqp?
   AMQP stands for Advanced Message Queuing Protocol. AMQP is an open standard protocol used for message-oriented middleware. It acts as a specific set of communication rules and data formats for the publisher and subscriber. They use AMQP to talk to the message broker (RabbitMQ) to send, receive, and queue events.
2. What is guest:guest@localhost:5672?
   This string is a connection URL that provides the necessary credentials and location details for the code to connect to the RabbitMQ server. The first guest acts as the default username. The second guest is the default password. Localhost:5672 is the address of the message broker. This means RabbitMQ will locally run in port 5672 in our machine. 