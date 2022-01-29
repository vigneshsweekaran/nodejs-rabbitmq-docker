# nodejs-rabbitmq-docker

### For publishing some messages to qeues
```
docker-compose exec consumer /bin/bash -c 'for ((i=1;i<=15;i++)); do node publisher.js; done'
```

### Reference
https://geshan.com.np/blog/2021/07/rabbitmq-docker-nodejs/#run-rabbitmq-with-docker-and-docker-compose
