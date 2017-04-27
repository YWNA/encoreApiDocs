* ### 接口请求格式：协议://服务器地址/版本号/接口地址及其参数/app\_key/时间戳/sign

### 

1. 协议，默认为http。

2. 服务器地址，例如api.host.com。

3. 版本号，例如：V001，V002。

4. 接口地址及其参数，例如：news/1/1。

5. app\_key，APP客户端使用登录接口成功后将会获得服务器端返回的参数信息，该参数信息包括app\_key和app\_key\_value。                

   接口返回内容：

   {"code":1,"data":{"app\__key":"_app\__key123","app_\_key\_value":"_app_\_key\_value456"}}

   > app\_key：将会在其它接口中使用，作为APP客户端已登录的唯一标识用户。
   >
   > app\_key\_value：将会用于生成sign值，APP客户端需要保存该值，且不该暴露在接口中。

6. 时间戳，时间戳的精细度到秒。

7. sign，使用hash-sha256获取到如下格式字符串的哈希散列值，/版本号/接口地址及其参数/app\__key/_时间戳_app\__key\_value  
   `/V001/magazine/newest/chenbo/1492850540456`

        字符串末尾

