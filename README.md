# private-isu-er

## 

```sh
docker run -v "$PWD/schema:/output" --net="host" schemaspy/schemaspy:snapshot \
-t mysql -host {DBのIP}:3306 -db {DB} -u {user} -p {password} -connprops useSSL\\=false allowPublicKeyRetrieval\\=true -s {schema}
```

## deploy

```sh
npm run deploy
```
