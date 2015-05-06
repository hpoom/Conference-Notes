# Patterns for API Centric architectures 

## Daniel Cerecedo - @dcerecedo - 6 May 2015

Works for Byteflair - http://byteflair.com/en/

Stateless. It means many things to many people. For him stateless means the Server does not maintain the Clients state.

The client might maintain its own state.

The orchestration of tasks is complex. Example of buying a product. Reduce stock, take payment, send email, order shipping, etc. Some processes are dependant on the outcome of the previous process.

Mediation Engine or Mediation Router is a way to orchestrate this.

- Load Balancing
- Dead Letter
- Content Based Routing
- Dynamic Router
- Normalizer

All written with Java JVM. [Apache Camel](http://camel.apache.org/)

Sometimes a message broker is needed to guarantee the delivery of a message. RabbitMQ the example.



