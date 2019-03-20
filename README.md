# README

## Generate rails application

```
docker-compose run web rails new . --force --no-deps --database=postgresql -T
```

## Install webpacker

```
docker-compose run web rails webpacker:install
```


## Create database

```
docker-compose run web rails db:create
```

## Run 

```
docker-compose run
```

## Stop

```
docker-compose down
```
