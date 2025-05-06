## 文件目录

### main目录

- stay等文件的根目录，从git下载后解压到main即可。

### redis目录

- redis 数据及配置目录
- 在redis/conf/redis.conf修改配置 (注意修改weChatPadPro对应参数)

### mysql目录
- 存放mysql容器相关文件——自动生成


## 运行
```
    docker compose up -d
    # 或者
    docker-compose up -d
```