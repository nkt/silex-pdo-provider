Silex PDO Service Provider
==========================

[![Build Status](https://travis-ci.org/nkt/flame.svg?branch=master)](https://travis-ci.org/nkt/silex-pdo-provider)

Silex provider for PDO

Usage
-----

```php
$app->register(new \Silex\Provider\PDOServiceProvider, array(
  'pdo.dsn'        => 'mysql:host=localhost;dbname=foobar',
  'pdo.username'   => 'nkt',
  'pdo.password'   => 'hello world',
  'pdo.attributes' => array(), // empty array by default
  'pdo.class_name' => 'MyCustomPDOClass' // PDO by default
));
```

License
-------
MIT
