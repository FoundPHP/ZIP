# ZIP
FoundPHP 框架下采用PHP开发的压缩类，支持PHP5/PHP7/PHP8等多版本。

```php
<?php
//解压缩
include 'zip.php';
$FoundPHP_zip	= new FoundPHP_zip();

//设置压缩文件密码
//$FoundPHP_zip->password('FoundPHP_zip');

//压缩文件与目录
$FoundPHP_zip->zip('foundphp.zip',array('foundphp.php','test/'));

//解压缩压缩文件与目录
$FoundPHP_zip->zip('foundphp.zip','zip/');

```
