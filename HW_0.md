| Database      | CAP characteristic |
| --------------| ------------------ |
| DragonFly     | CP                 |
| ScyllaDB      | AP                 |
| ArenadataDB   | CA                 |

## Explanation

1. ### DragonFly
   The DragonFly database is often compared to Redis. Even on its [official website](https://www.dragonflydb.io/), it is referred to as "Redis with wings". Therefore, it is logical to assume that this database inherits characteristics from Redis: Consistency and Partition tolerance.
3. ### ScyllaDB
   According to [this part](https://opensource.docs.scylladb.com/stable/architecture/architecture-fault-tolerance.html#:~:text=ScyllaDB%20chooses%20availability%20and%20partition%20tolerance%20over%20consistency%2C%20such%20that%3A) of the official documentation:
   
   > ScyllaDB chooses availability and partition tolerance over consistency, such that:
   > - It’s impossible to be both consistent and highly available during a network partition;
   > - If we sacrifice consistency, we can be highly available.
4. ### ArenadataDB
Since ArenadataDB is an analytical data base, I researched some of it's analogues, and came up with my answer based on this analysis.
