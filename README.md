# Social Networking System

This is a backend social networking system based on Python and Django, aiming for industry use with low latency and high throughput. It provides APIs for building friendships, posting messages and photos, news feeds, giving comments and likes, pushing notifications, etc. It adopts Redis, Memcached, denormalization, and HBase to reduce database queries and increase query efficiency. It uses Message Queue to deliver asynchoronized tasks and cut down response time.


## Technologies

| Technology           | Description          | Website                                           |
| -------------------- | ------------------- | ---------------------------------------------- |
| Django               | Python-based MVC framework   | https://www.djangoproject.com/        |
| DjangoRESTframework  | REST framework               | https://www.django-rest-framework.org/     |
| MySQL                | Sql DB           | https://www.mysql.com/                      |
| HBase                | NoSql DB         | https://hbase.apache.org/                      |
| Memcached            | Distributed in-memory cache        | https://memcached.org/       |
| Redis                | Distributed in-memory cache        | https://redis.io/            |
| RabbitMQ             | Message Queue    | https://www.rabbitmq.com/                      |
| Amazon S3            | Object storage service        | https://www.amazon.com/aws/s3            |



## Models & APIs

<img width="1440" alt="image" src="https://user-images.githubusercontent.com/70275050/178489411-de28b355-2210-48c2-bceb-0d27fed80b65.png">
<img width="1440" alt="image" src="https://user-images.githubusercontent.com/70275050/178489340-77cb7ab5-649e-457a-84b8-a0fcf102803c.png">
