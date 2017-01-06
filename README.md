# QQWry

纯真 IP 库 thinkphp 版 。

数据库版本：2016.3.26

## 安装

```
composer require tp3/qqwry
```

更新你的依赖包 ```composer update``` 或者全新安装 ```composer install```。

## 使用

## 例子

### Facades用法
```php
	use \juju\qqwry\QQWry;
    $ip = '61.128.128.68';
    print_r((new QQWry())->getlocation($ip));
```

