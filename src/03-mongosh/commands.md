## Connect to container

```sh
docker-compose exec mongodb bash
```
## Connect with mongosh

```sh
mongosh "mongodb://root:root123@localhost:27017/?authMechanism=DEFAULT&tls=false"
mongosh "mongodb+srv://carloadmin:carloadmin123@mongodb101.aailwtf.mongodb.net/test"
```

```sh
show dbs
show collections
```

```sh
use("Platzi_store")
db.products.find()

```

