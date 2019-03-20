# Akka MassTransit Logger

How To Use
---------------
Add `Akka.MassTransit.Logger` as reference to your Akka.Net project.

Edit logging in hocon file
E.G.:
```
loggers = ["Akka.MassTransit.Logger.QueueLogger, Akka.MassTransit.Logger"]
queue-uri = "rabbitmq://localhost/logging_akka"
```
Start MassTransit and Set `AkkaService.Bus` to hold reference to the new MassTransit instance

<b>My Love for `Dictionary<string,string>` was born out of Love for JSON - Serializing and Deserializing - and not needing to worry about FUTURE data that maybe required to be passed around</b>
