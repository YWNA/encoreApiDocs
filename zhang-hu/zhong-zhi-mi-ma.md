* 接口地址：/account/resetpass

* 提交方式：POST

* 接口参数：

  * phone：手机号码

  * code：验证码

  * password：密码

  * password\_repeat：重复密码

* 接口返回：

  * code为空时

  ```json
  {
      "code": 1,
      "data": "短信息发送成功"
  }
  ```

  * 接口参数都填写

  ```json
  {
      "code": 1,
      "data": true
  }
  ```



