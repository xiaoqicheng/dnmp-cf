# redis 去中心化集群部署
### 部署教程 https://redis.io/topics/cluster-tutorial

#在三台机器上分别部署 部署完成后执行
redis-cli --cluster create 192.168.75.129:6379 192.168.75.131:6379 192.168.75.132:6379  --cluster-replicas 0 (无从机 都是主机)