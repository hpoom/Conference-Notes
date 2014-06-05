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

#### Query everything search

- ElasticSearch
- Solr

Range, span, and ketword queries.

You can score things to boost them up the results.

*Facets* in ElasticSearch are easy. They are not so easy in Relational DB.
Facets are excellent for logs 

#### Key: Value DB's

- redis
- riak

#### Columnar DB's

Flip the data to be more how it is layed out on disk. *See slides for understanding*

Great for stuff that is analytical.
InfoBright is a MySQL extension to achive Columnar DB.

#### Cell level security

NSA made a Cell Level DB, then open sourced it. Not many other examples of this.

#### Time series DB's

Still emerging in the NoSQL area. Time series is not so hard to achive in Traditional DB's. SQL DB's might win this one.

#### Graph DB's

- Neo4j
- *Others but did not catch as slides moved on. See slides*

In speakers words **Graph DB's are awesome**.

#### Big Data DB's

- Hadoop

SQL on top of Hadoop. SQL layers *see slides*.

#### Summary

ACID = Traditonal SQL  
BASE = NoSQL

**A**tomic  
**C**onsistent  
**I**solated  
**D**urable  

**B**asiclly **A**vailable  
**S**oft-state  
**E**ventually consistent  

Finishes with explination that there is a case for both SQL and NoSQL solutions. Depending on what you are doing, *choose the right tool for the job*.




