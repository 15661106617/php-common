# PHP-JOIN-COMMON php 常用公共类

### composer 安装
需要 composer 版本2+

```
composer require join/php-common
```
### require 依赖

php：>=7.2.0

## 代码结构
```
├─src
│  ├─encrypt
│  │      SM4.php               国密4加解密
│  └─utils
│          FFmpeg.php           视频处理
│          JwtAuth.php          jwt授权帮助类
│          Pinyin.php           拼音处理
│          Text.php             文本处理
│          Tree.php             树数据处理
```

### 如何参与开发成为代码贡献人员

1. 将项目fork到自己帐号
2. 修改代码完成测试
3. 提交commit push 到自己的仓库
3. New pull request(简称pr) 合并请求到主库等待合并
