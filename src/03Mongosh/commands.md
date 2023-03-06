# Connect to container

```sh
docker-compose exec mongodb bash
```

# Connect with mongosh

```sh
mongosh "connection url"
```

```sh
show dbs
show collections
```

```sh
use("platzi_store")
db.products.find()
```