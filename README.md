## 文件目录

### main 目录

- stay 等文件的根目录，从 git 下载后解压到 WeChatPadPro 即可。

### setting.json配置

- 自动映射配置文件setting.json到WeChatPadPro/assets/setting.json

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
    docker compose down
    # 或者
    docker-compose down
```

### 下载更新文件

- 从 git 重新下载WeChatPadPro的 执行文件等，放入./WeChatPadPro
- 建议更新前备份原./WeChatPadPro为./WeChatPadPro-bak

### 重启容器

```
    docker compose up -d
    # 或者
    docker-compose up -d
```
