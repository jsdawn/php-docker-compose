# demo-docker-compose

demo of php project built by docker compose

利用 docker-compose 编排 PHP 项目的一个 demo，旨在构建一个简单的 PHP 开发环境

## docker-compose start

```bash
# 构建并运行容器
docker-compose up -d

# 清缓存并重新构建其镜像（指定服务），不指定则构建全部
docker-compose build --no-cache nginx

# 停止并移除所有容器，并删除相关的镜像
docker-compose down --rmi all
```
