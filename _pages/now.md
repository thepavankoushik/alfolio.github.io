---
layout: page
permalink: /now/
title: now
description: What I am doing right now?
nav: true
nav_order: 1
---


Currently I am trying to build my own `Redis` database, from scratch. Right now I am very much focused on getting it working, not worrying much about the code organisation. 

Some of the tasks I am trying to complete are:
0. RESP (Redis communication protocol, probably I will use this in my CLI wrapper too.)
1. Event Loops (Redis runs on single thread, it is very interesting to build something that is fast and supports concurrency, without the use of threads)
2. Replication (well, everyone read master slave architecture on paper, but very few might have had chance writing it, along with replication and communication)
3. Persistance
4. Streams 

In the second iteration, I will be focusing on making it into a standalone database, with `CLI Wrapper`, `solid SOLID principles`, `OOPS` .

Resources I am referring:
+ [codecrafters](https://app.codecrafters.io/courses/redis/introduction)
+ [JSConf](https://www.youtube.com/watch?v=8aGhZQkoFbQ&ab_channel=JSConf)
+ [Redis RESP 1](https://redis.io/docs/reference/protocol-spec/)
+ [Redis RESP 2](https://lethain.com/redis-protocol/)
+ [Redis Replication](https://redis.io/docs/management/replication/)


Last Updated on: April 3rd, 2024