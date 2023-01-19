# Django Twitter Backend Service

## Introduction
A backend social networking service based on Python and Django, aiming for low latency and high throughput. It provides APIs for building friendships, posting messages and photos, news feeds, giving comments and likes, pushing notifications, etc.

- Built low-latency SNS backend using Python, Django & RESTful API.
- Implemented newsfeeds using push model, and implemented endless pagination for mobile-friendly user experience.
- Reduced queries for read-heavy tables by using Redis and Memcached. 
- Reduced database queries by using denormalization to store numbers of comments and likes.
- Improved database query performance of friendships and newsfeeds by adopting HBase to support range queries.
- Reduced response time by leveraging Redis as message queue to deliver asynchronized tasks.
- Committed over 10000 lines of code changes, spent over 3 months to finish.

## Technologies

| Technology           | Description          | Website                                           |
| -------------------- | ------------------- | ---------------------------------------------- |
| Django               | Python-based MVC framework   | https://www.djangoproject.com/        |
| DjangoRESTframework  | REST framework               | https://www.django-rest-framework.org/     |
| MySQL                | Sql DB           | https://www.mysql.com/                      |
| HBase                | NoSql DB         | https://hbase.apache.org/                      |
| Memcached            | Distributed in-memory cache        | https://memcached.org/       |
| Redis                | Distributed in-memory cache        | https://redis.io/            |
| Amazon S3            | Object storage service        | https://www.amazon.com/aws/s3            |
