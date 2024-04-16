# Redis Stack
## Extends Redis with modern data models and processing engines. Includes documentation for the bundled Redis modules and RedisInsight.


Redis Stack is an extension of Redis that adds modern data models and processing engines to provide a complete developer experience.

In addition to all of the features of OSS Redis, Redis Stack supports:

* Queryable JSON documents
* Full-text search
* Time series data (ingestion & querying)
* Probabilistic data structures

## Getting started

To get started with Redis Stack, see the [Getting Started](https://redis.io/docs/stack/get-started/) guide. You may also want to:

* [Install Redis Stack](https://redis.io/docs/latest/operate/oss_and_stack/install/install-stack/)
* [See the list of clients supporting Redis Stack](https://redis.io/docs/latest/develop/connect/clients/)
* [View the Redis Stack tutorials](https://redis.io/docs/latest/develop/get-started/)

If you want to learn more about the vision for Redis Stack, read on.

## Why Redis Stack?

Redis Stack was created to allow developers to build real-time applications with a backend data platform that can reliably process requests in under a millisecond. Redis Stack does this by extending Redis with modern data models and data processing tools (Document, Search, and Time Series).

Redis Stack unifies and simplifies the developer experience of the leading Redis modules and the capabilities they provide. Redis Stack bundles five Redis modules: [RedisJSON](https://redis.io/docs/latest/develop/data-types/json/), [RediSearch](https://redis.io/docs/latest/develop/interact/search-and-query/), [RedisTimeSeries](https://redis.io/docs/latest/develop/data-types/timeseries/), and [RedisBloom](https://redis.io/docs/latest/develop/data-types/probabilistic/).

### Clients

Several Redis client libraries support Redis Stack. These include [redis-py](https://github.com/redis/redis-py), [node_redis](https://github.com/redis/node-redis), [NRedisStack](https://github.com/redis/NRedisStack), and [Jedis](https://github.com/redis/jedis). In addition, four higher-level object mapping libraries also support Redis Stack: [Redis OM .NET](https://github.com/redis/redis-om-dotnet), [Redis OM Node](https://github.com/redis/redis-om-node), [Redis OM Python](https://github.com/redis/redis-om-python), [Redis OM Spring](https://github.com/redis/redis-om-spring).

### RedisInsight

Redis Stack also includes RedisInsight, a visualization tool for understanding and optimizing Redis data.

## Redis Stack license

Redis Stack is made up of several components, licensed as follows:

* Redis Stack Server, which combines Redis with RediSearch, RedisJSON, RedisTimeSeries, and RedisBloom, is licensed under the [Redis Source Available License 2.0](https://github.com/RediSearch/RediSearch/blob/master/LICENSE.txt) (RSALv2) or the [Server Side Public License](https://en.wikipedia.org/wiki/Server_Side_Public_License) (SSPL).

* RedisInsight is licensed under the [Server Side Public License](https://en.wikipedia.org/wiki/Server_Side_Public_License) (SSPL).
