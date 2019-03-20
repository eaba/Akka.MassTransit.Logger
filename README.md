# Akka MassTransit Logger

How To Use
---------------
Add `Akka.MassTransit.Logger` as reference to your Akka.Net. Edit logging in hocon file
E.G.:
```
loggers = ["Akka.MassTransit.Logger.QueueLogger, Akka.MassTransit.Logger"]
queue-uri = "rabbitmq://localhost/logging_akka"
```
Start MassTransit and Set `AkkaService.Bus` to hold reference to the new MassTransit instance
