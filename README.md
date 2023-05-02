#  Deploying prometheus on local custer consists of 4 pis based on https://phoenixnap.com/kb/prometheus-kubernetes with some further adaptation;
## About NFS Server, cat /etc/exports
```/mnt/nfs/promdata *(rw,sync,no_subtree_check)```
### You may test it by using command like,
```sudo mount -t nfs 192.168.11.113:/mnt/nfs/promdata /mnt/nfs/promdata```
# prometheus_on_local_pi_cluster
![alt text](https://i.ibb.co/xYxfKqw/prom-desktop.jpg)
