# example-laravel-caddy-letsEncrypt
# Laravel with CaddyServer 

### Create directory 

```shell
mkdir web
```

## open directory

```shell
cd web
```

### Copy env config

```shell
cp env-example .env
```

### Edit config Caddyfile file

```shell
rename root /var/www/{your_project}/public
```

### Runserve project

```shell
 docker-compose up -d caddy
```

## Verify service http://localhost

