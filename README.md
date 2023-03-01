# BaiduBce CDN PHP SDK

PHP SDK包要求运行环境至少为PHP 5.3.9 版本(暂不支持PHP 8及以上版本)，如 5.4、5.5、5.6、7.0、7.1、7.2、7.3。


## 安装
~~~
composer require axguowen/baidubce-cdn
~~~

## 创建CdnClient
~~~php
use BaiduBce\BceClientConfigOptions;
use BaiduBce\Util\Time;
use BaiduBce\Util\MimeTypes;
use BaiduBce\Http\HttpHeaders;
use BaiduBce\Services\Cdn\CdnClient;
//调用配置文件中的参数
global $g_CDN_TEST_CONFIG;
//新建CdnClient
$client = new CdnClient($g_CDN_TEST_CONFIG);
~~~