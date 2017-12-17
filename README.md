# php-cli-alpine

run php-cli-alpine in docker

## build 
```
docker build -t heropoo/php-cli-alpine .
```

## run 
```
docker run --rm -ti -v $PWD/www/:/src/www -p 8080:80 heropoo/php-cli-alpine
```

run by docker-compose 
```
docker-compose up
```