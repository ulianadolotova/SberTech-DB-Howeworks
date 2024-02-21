| Database      | CAP characteristic |
| --------------| ------------------ |
| DragonFly     |                    |
| ScyllaDB      | AP                 |
| ArenadataDB   |

## Explanation

1. ### DragonFly
2. ### ScyllaDB
   According to [this part](https://opensource.docs.scylladb.com/stable/architecture/architecture-fault-tolerance.html#:~:text=ScyllaDB%20chooses%20availability%20and%20partition%20tolerance%20over%20consistency%2C%20such%20that%3A) of the official documentation:
   
   > ScyllaDB chooses availability and partition tolerance over consistency, such that:
   > - It’s impossible to be both consistent and highly available during a network partition;
   > - If we sacrifice consistency, we can be highly available.
4. ### ArenadataDB
