# Laravel学习笔记

### 安装
1. composer 安装
```shell
composer create-project laravel/laravel projectName
// 安装指定版本
composer create-project 'laravel/laravel:8.*' projectName
```

2. laravel 安装
```shell
laravel new projectName
```
3. docker
```shell
curl -s "https://laravel.build/example-app" | bash
./vendor/bin/sail up
```
> Tips: [https://laravel.build/example-app访问不到，可以在浏览器中复制脚本，在命令行中执行](https://laravel.build/example-app)
