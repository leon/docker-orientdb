# OrientDB
OrientDB is a 2nd Generation Distributed Graph Database with the flexibility of Documents in one product with an Open Source commercial friendly license (Apache 2 license). First generation Graph Databases lack the features that Big Data demands: multi-master replication, sharding and more flexibility for modern complex use cases.

## Run

```bash
docker run -d --name orientdb -P leon/orientdb:latest
```

## Environment variables
```
ORIENTDB_VERSION orientdb-community-2.0.3
ORIENTDB_URL http://www.orientechnologies.com/download.php?email=unknown@unknown.com&file=${ORIENTDB_VERSION}.tar.gz&os=linux
ORIENTDB_ROOT_PASSWORD orientdbmasterpassword
ORIENTDB_BACKUP false
```

## Expose
```
2424
2480
```

## Volumes
```
/etc/orientdb
/var/lib/orientdb/data
/var/log/orientdb
```
