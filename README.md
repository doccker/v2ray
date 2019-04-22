# v2ray 使用说明

docker-compose up -d

1.使用服务50344监听nginx的SSL，使用/ray代理到v2ray60512端口

2. 客户端配置如下

address: tu.rtoken.vip : 50344

alterID:100 Level:0

Security:  auto


Network: ws



WebSocket{ path : /ray

TLS : Use TLS -> TLS allowInsecure  -> ServerName: tu.rtoken.vip
