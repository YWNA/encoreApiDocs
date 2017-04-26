* 接口请求格式

http://服务器地址/版本号/接口地址及其参数/app\_key/时间戳/sign

* APP客户端使用登录接口成功后将会获得服务器端返回的参数信息，该参数信息包括app\__key和app\_key\_value。_

```
{"code":1,"data":{"app_key":"123","app_value":"456"}}
```

> app\_key：将会在其它接口中使用，作为APP客户端已登录的唯一标识用户。
>
> app\__key\__value：将会用于生成sign值，APP客户端需要保存该值，且不该暴露在接口中。


