# fast-api
fast-api 基于Laravel简洁、优雅的PHP Web开发框架(PHP Web Framework)。它可以让你从面条一样杂乱的代码中解脱出来；它可以帮你构建一个完美的前后端分离项目，而且每行代码都可以简洁、富于表达力，它提供了一种更容易表达的方式来创建。

更多功能可以参考下面的文档。

- [简介](#安装与配置)
    - [安装](#安装)
        - [配置数据库](#配置数据库)
        - [数据迁移](#数据迁移)
        - [生成数据](#生成数据)
- [启动](#启动)
- [文档](#文档)
- [演示](#演示)
- [完整项目](#完整项目)
- [存储库](#存储库)
- [bug、建议、贡献和支持](#bug-建议-贡献和支持)
- [版权和许可](#版权和许可)


## 简介
![image](https://logo.aliyun.com/logo/image?goodsId=789c09932931073747addca94bbe3c93&type=png)

## 安装

安装依赖和框架

```sh
composer install
```

## 配置数据库

```ini
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=fast-api
DB_USERNAME=root
DB_PASSWORD=root
```

## 数据迁移

```sh
php artisan migrate --path=vendor/fast-api/permission/database/migrations
```

## 生成数据

```sh
php artisan db:seed --class=AdminUserSeeder
```

## 启动本地开发环境

```sh
php artisan serve
```

## 文档
PHP开发技术交流（QQ群 368868750）

[![PHP开发技术交流 (SDK)](http://pub.idqqimg.com/wpa/images/group.png)](https://qm.qq.com/cgi-bin/qm/qr?k=rfRumoZ0fxUN4TdshfjkxiHximnHVSzb&jump_from=webapi)

> fast-api-permission 是基于laravel 7.x 封装，在做项目开发前，必需先阅读laravel官方文档。
>* laravel 官方文档：https://learnku.com/docs/laravel/7.x/releases/7444

## 演示
后台地址
> https://fast-admin.dnat.link
> 
> 账号: admin
>
> 密码: 123123

API文档
> https://fast-api.dnat.link/api/documentation


## 完整项目

后台仓库地址：
> Github
>
> https://github.com/fast-oopdev/fast-admin.git

API仓库地址：
> Github
>
> https://github.com/fast-oopdev/fast-api.git


## 存储库
> fast-api
>* GitHub 托管地址：https://github.com/fast-oopdev/fast-api-permission
> 
> fast-admin
>* GitHub 托管地址：https://github.com/fast-oopdev/fast-admin-permission
> 
> fast-api/permission
>* packagist 托管地址：https://packagist.org/packages/fast-api/permission
>

## bug 建议 贡献和支持

请使用[Github](https://github.com/fast-php/fast-api-permission)报告bug，并提出意见或建议。

请参阅[CONTRIBUTING.md](CONTRIBUTING.md)了解如何贡献更改。


## 版权和许可

[fast-api](https://github.com/fast-oopdev/fast-api)
was written by [fast-oopdev](http://www.dnat.link) and is released under the
[MIT License](LICENSE.md).

Copyright (c) 2021 fast-api