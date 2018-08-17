### 事前準備

```
$ cd vue-hackernews-2.0-master
$ docker-compose run --rm --no-deps frontend yarn install
```

### 起動方法

```
$ cd vue-hackernews-2.0-master
$ docker-compose up
```

### 再インストール

```
$ cd vue-hackernews-2.0-master
$ rm -rf node_modules
$ rm -rf yarn.lock
$ docker-compose run --rm --no-deps frontend yarn install
$ docker-compose up
```
