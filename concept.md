# Load balancing
# Caching (Cache)

```mermaid
app[Application]
cach[Memcached]
db[Slow database]

app --> cache
cach --> app
db -.-> app

```
