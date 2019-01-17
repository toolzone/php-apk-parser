# [Apk Parser](http://tufanbarisyildirim.github.io/php-apk-parser/)

此包可以提取运行在Android操作系统上的设备使用的APK格式的应用程序包文件。
它可以打开一个APK文件并提取包含的清单文件来解析它并检索元信息。
它包含应用程序名称、说明、所需的设备功能访问权限等。
类还可以将APK文件中包含的整个文件提取到给定的目录中。

### 要求

PHP 5.3+

### 安装

- 安装 [composer](http://getcomposer.org/download/)
- 在项目中创建composer.json，如下示例：

```json
{
    ...
    "require": {
        "tufanbarisyildirim/php-apk-parser":"dev-master"
    }
}
```

- 然后在'composer.json'的文件夹执行：`php composer.phar install' 或 'composer install'
