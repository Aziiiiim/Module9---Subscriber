# Reflection

## a. What is AMQP?

**AMQP** (Advanced Message Queuing Protocol) is a standardized messaging protocol that enables systems to communicate with each other via message queues in a reliable, asynchronous, and decoupled manner.

It is often used in message brokers like RabbitMQ to support **publish/subscribe** and **message queuing** patterns. AMQP defines how messages are formatted, sent, routed, and received between systems.

---

## b. What does it mean? guest:guest@localhost:5672, what is the first guest, and what is the second guest, and what is localhost:5672 is for?

This is a connection URI used to connect to the RabbitMQ server using AMQP protocol:

- **First `guest`**: This is the **username** used to log into RabbitMQ.
- **Second `guest`**: This is the **password** for that username.
- **`localhost`**: This means the RabbitMQ server is running on the **local machine**.
- **`5672`**: This is the **default AMQP port** used by RabbitMQ to listen for incoming client connections.
