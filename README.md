## 文件目录

### main 目录

- stay 等文件的根目录，从 git 下载后解压到 main 即可。

### redis 目录

- redis 数据及配置目录
- 在 redis/conf/redis.conf 修改配置 (注意修改 weChatPadPro 对应参数)

### mysql 目录

- 存放 mysql 容器相关文件——自动生成

## 运行

```
    docker compose up -d
    # 或者
    docker-compose up -d
```

## 更新:

### 停止容器

```
    docker compose up -d
    # 或者
    docker-compose up -d
```

### 下载更新文件

- 从 git 重新下载 WeChatPadPro，放入 main

### 重启容器

```
    docker compose up -d
    # 或者
    docker-compose up -d
```
