# docker-shadowsocks
用alpine镜像构建的docker shadowsocks服务端容器，大小只有 51.72 MB

# 使用方法
```
git clone https://github.com/bingoku/docker-shadowsocks.git cd docker-shadowsocks docker-compose up -d 
```

# 配置修改
```
{
    "server":"0.0.0.0",
    "local_address": "127.0.0.1",
    "local_port":1080,
    "port_password":{
         "8989":"QTMDGFW",
         "9001":"QTMDGFW",
         "9002":"QTMDGFW",
         "9003":"QTMDGFW",
         "9004":"QTMDGFW"
    },
    "timeout":300,
    "method":"aes-256-cfb",
    "fast_open": true
}
```
