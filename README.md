# registry

Docker registry in one step with HTTPS certificate provided by [Caddy](https://caddyserver.com/) and [Let's Encrypt](https://letsencrypt.org/).


# installation

1. Change `your.registry.com` and `your.email@your.registry.com` with your actual addresses in `./caddy/Caddyfile`  
2. Change (if you want of course) `./registry/htpasswd` for your file (current includes `admin/admin`)
3. Run with `docker-compose up -d`


# copyright

Daniil Sliusar for [netegis](https://github.com/netegis) in 2021.