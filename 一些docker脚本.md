```
https://zhuanlan.zhihu.com/p/74082157
```



duplicati备份工具：

```
sudo docker run -d --restart unless-stopped --name=duplicati -p 8200:8200 -v /home/hanhongyong/docker/duplicati/config:/config -v /home/hanhongyong/docker/duplicati/backups:/backups -v /home/hanhongyong/code:/source -e PUID=1000 -e PGID=1000 -e TZ=Asia/Shanghai  linuxserver/duplicati:latest
```

