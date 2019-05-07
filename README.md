# hexo-deployer-upyun2019

hexo博客又拍云部署2019版

# 安装

```
npm install hexo-deployer-upyun2019 --save
```

# 用法

编辑根目录的`_config.yml`文件的`deploy`字段

配置又拍云存储的服务名称、操作员名称、操作员密码

```
deploy:
  - type: upyun
    serviceName: 服务名称
    operatorName: 操作员名称
    operatorPassword: 操作员密码
    path: / 上传目录(选填，默认为根目录)
```

