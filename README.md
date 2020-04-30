# Laravel with CaddyServer 

## Create directory 

```shell
mkdir web
```

## Open directory

```shell
cd web
```

## Clone repository application

```shell
git clone https://github.com/viniciusnascimento95/example-laravel-caddy-letsEncrypt.git 
```

## Clone repository application

```shell
git clone https://your-repository.git 
```

## View directory

  web/
    example-laravel-caddy-letsEncrypt/
    your_application/

## Open directory

```shell
cd example-laravel-caddy-letsEncrypt
```

## Copy env config

```shell
cp env-example .env
```

## Edit config file Caddyfile 

```shell
edit line with name your project -- /var/www/{your_project}/public
```

## Runserve project

```shell
 docker-compose up -d caddy
```

## Verify service http://localhost
