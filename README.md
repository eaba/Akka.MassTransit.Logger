# Akka MassTransit Logger

How To Use
---------------
Edit logging in hocon file
E.G.:
```
loggers = ["Akka.MassTransit.Logger.QueueLogger, Akka.MassTransit.Logger"]
queue-uri = "rabbitmq://localhost/logging_akka"
