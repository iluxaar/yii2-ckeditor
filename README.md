Yii2 Ckeditor
===============
Yii2 Ckeditor

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist iluxaar/yii2-ckeditor "*"
```

or add

```
"iluxaar/yii2-ckeditor": "*"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply use it in your code by:

```php
<?=
\iluxaar\ckeditor\Ckeditor::widget();
?>
```