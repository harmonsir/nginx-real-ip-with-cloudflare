# nginx-real-ip-with-cloudflare

nginx使用cloudflare时，显示用户的真正ip，并限制仅能通过cloudflare连接服务器。

## setup 
安装方法

```
wget https://github.com/harmonsir/nginx-real-ip-with-cloudflare/raw/main/plug_cloudflare_ip.conf -O /etc/nginx/conf.d
wget https://github.com/harmonsir/nginx-real-ip-with-cloudflare/raw/main/plug_cloudflare_only.conf -O /etc/nginx/conf.d
nginx -t
```

