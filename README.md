# vault-consul-swarm-cluster


## Deploy Stack
```
env $(cat .env | grep ^[A-Z] | xargs) docker stack deploy -c stack.yml devops
```

## Remove Stack
```
docker stack rm devops
```

## List Docker Services
```
docker service ls
```

## Access Vault UI
```
open http://localhost:8200
```

## Access Consul UI
```
open http://localhost:8500
```
