# caddy-cloudflare-dns
Caddy V2 &amp; Cloudflare DNS ACME DNS-01 challenge


```shell

docker buildx create --use --name mybuilder

docker buildx build github.com/itsprakashp/caddy-cloudflare-dns -t itsprakashp/caddy-cloudflare-dns:2.7.6 -t itsprakashp/caddy-cloudflare-dns:latest --push

docker buildx build github.com/itsprakashp/caddy-cloudflare-dns -t itsprakashp/caddy-cloudflare-dns:2.7.6-arm64 -t itsprakashp/caddy-cloudflare-dns:latest-arm64 --push

```