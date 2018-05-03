# local-npm-cache
Run a local proxying npm cache for scenarios with bad connectivity.
Caches npm packages on local disk.

Based on https://github.com/verdaccio/docker-examples/tree/master/docker-local-storage-volume

## Usage
Initially configure npm to use the local registry
```sh
npm set registry http://localhost:4873/
```

Start the docker container
```sh
docker-compose up
```