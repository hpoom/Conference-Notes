# When to NoSQL and when to Know SQL
## Simon Elliston Ball - @sireb - 5 June 2014 09:00

Redgate software

[slides](http://nosqlknowsql.io)

- SQL
- NoSQL
- Not only SQL
- no, SQL

Scale up. Add hardware to scale. Spend more money to scale!

Scaling now lots of small boxes, instead of one huge box.

We have now moved to Micro Services and API's (Agree 100%, line from my FOWA talk)

Fewer migrations headaches with NoSQL, comapared to Traditional Relational DB's

NoSQL works well for social, because much of came out of social

#### Document DB's

- mongoDB
- CouchDB
- RavenDB

They are: Rapid dev, JSON docs, variable models, known access pattern
Mnetioned Hood.ie as dev stack for FEDs so they don't need to worry about a backend. It is CouchDB based.

**Don't join in any doucment database!**

Traditional relational databases have started pushing NoSQL document fetures into their Relational databases. So they sub parse JSON or XML when it is a blog in a ralational database. Native JSON support appearing in Postgress *JSONB*. MySQL anounce support for native JSON last month.

#### 