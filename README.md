# webiss

### Add the following code to the beginning of php code in `system/bootstrap.php.inc` to get it fixed:
````
$_SERVER['HTTPS'] = 'on';
$_SERVER['SERVER_PORT'] = '443';
````
