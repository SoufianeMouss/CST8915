# Lab 7 - CST8915 Full-stack Cloud-native Development: Introduction to Kubernetes Basics

## Demo Video
[Lab 7 Video](https://www.awesomescreenshot.com/video/46419809?key=7927989d7098dadaf1966c70eccd44b2)

## RabbitMQ configuration issues
1. Based on my testing RabbitMQ is stateless application
2. When we run RabbitMQ without persistent storage, RabbitMQ can't save the order queues.
3. When the RabbitMQ pod is deleted or restarted, the order queues are lost
4. The solutions we can implement is to :
    a. Use a persistent volume claim
    b. Replace RabbitMQ with Azure Service Bus
5. Yes Azure Service Bus solve the issues identified with RabbitMQ configuration, because it's a fully managed service that handles message persistence and high availabitity automatically without our interefence.