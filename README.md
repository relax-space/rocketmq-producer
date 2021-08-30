# rocketmq-producer

基于spring boot运行的rocket mq，需要和rocketmq-consumer配套使用

## start

+ 启动rocket mq,在docker-compose文件夹下执行以下命令【必须先安装docker】

```bash
docker-compose up -d
```

+ 启动项目：
    1. 配置maven settings，路径：setting/settings.xml
    2. 右键Application，然后点击Run 'Application.main()'

+ 测试：
    1. 方法1：运行测试文件ProducerAllTest的send()方法
    2. 方法2：浏览器上请求localhost:2001/mq/obj?count=1

## 引用

https://github.com/relax-space/rocketmq-producer

https://github.com/relax-space/rocketmq-consumer

https://github.com/apache/rocketmq-docker

https://code.aliyun.com/aliware_rocketmq/rocketmq-demo/tree/master?spm=a2c4g.11186623.0.0.6b1cb1a5Nhs26w