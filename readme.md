## 介绍
一个使用`Laravel`+`Swoole`的在线聊天室。

## 环境

- PHP >=7.0
- Laravel >= 5.5 
- MySQL 
- Swoole
- Redis

## 使用

1. 

```
git clone https://github.com/Hubins/swoole_chat.git
```

2.

```
composer install
```

3. 

```
cp .env.example .env
```

4.

```
php artisan key:generate
```

5.

```
php artisan storage:link
```

6.
 
```
php artisan migrate
```

7. 

```
php artisan swoole:action start
```