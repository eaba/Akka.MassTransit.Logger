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
`StartAsync` MassTransit and then assign it to `AkkaService.Bus` 

<b>My Love for `Dictionary<string,string>` was born out of love for JSON - Serializing and Deserializing - and not needing to worry about FUTURE data`(parameter(s), argument(s))` that maybe required to be passed around</b>
