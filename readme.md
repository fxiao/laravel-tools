# Laravel 快速开发工具包

目标：数据库设计好，整套后台管理和 RESTful API 规范的接口就出来了

## 源码清单

```
.
├── composer.json
├── LICENSE
├── readme.md
└── src
    ├── BaseTransformer.php
    ├── ControllerHelper.php
    ├── Controller.php
    ├── dev-helpers.html
    ├── HelpersController.php # 脚手架控制器
    ├── helpers.php
    ├── LumenToolsServiceProvider.php
    └── Scaffold
        ├── ControllerCreator.php
        ├── MigrationCreator.php
        ├── ModelCreator.php
        ├── RouteCreator.php
        ├── stubs
        │   ├── controller.stub
        │   ├── create.stub
        │   ├── model.stub
        │   ├── route.stub
        │   └── transformer.stub
        └── TransformerCreator.php
```

## 依赖

- PHP >= 7.2.8
- Laravel >= 6.x
- tymon/jwt-auth 
- dingo/api >= 2.4

## 安装

```bash
composer require fxiao/laravel-tools
```
