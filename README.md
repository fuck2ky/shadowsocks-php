
基于[swoole](https://github.com/swoole/swoole-src)扩展的shadowsocks实现

# Installation

Use [Composer](https://getcomposer.org/):

```sh
composer require losgif/shadowsocks-php dev-master
```

# Usage

```php
<?php
use Liubinzh\ShadowSocks\ShadowSocksServer;

$s = new ShadowSocksServer();
$s->start();
```

# 其他
加密类使用了[workerman版本](https://github.com/walkor/shadowsocks-php)的实现
