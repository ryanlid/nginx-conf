# nginx 配置文件

## 生成默认证书

```
sudo openssl req -x509 -nodes -days 365 -newkey rsa:2048 \
-keyout /usr/local/nginx/conf.d/key/default.key \
-out /usr/local/nginx/conf.d/key/default.crt
```
