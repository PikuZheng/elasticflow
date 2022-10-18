# elasticflow
Forked form gitee.com/qytang/ElasticFlow


usage:
```
mkdir -p /userdata/elasticsearch
cd /userdata/elasticsearch
wget https://github.com/PikuZheng/elasticflow/raw/main/docker-compose.yml -d docker-compose.yml
docker-compose up -d
```

**Warning: The entire system requires at least 5GB of physical memory.**
If the container displays "Exit code 137", it means that there is not enough physical memory.
