## 文件目录

### WeChatPadPro 目录

- stay 等文件的根目录，从 git 下载后解压到 WeChatPadPro 即可。

### setting.json配置
- 可按自己需求修改setting.json内容。若修改，请自行确保配置正确(与docker-compose.yml对应)。
- 该文件会在 WeChatPadPro/assets/setting.json 中自动映射。
- 主要配置项：
  - `port`: WeChatPadPro 的端口，默认 8849
  - `redisConfig`: redis 的连接信息因此在这里配置时应为 `redis:6379`
  - `mySqlConnectStr`: mysql 的连接信息

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
