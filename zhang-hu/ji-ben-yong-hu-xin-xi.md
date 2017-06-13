* 接口地址：/account/info

* 提交方式：POST

* 接口参数：

  * sinature：用户的手机号码

  * username：用户的密码

  * sex：0为女，1为男，2为无

  * country：国家名称

  * pro：省名称

  * area：市（区）名称

* 接口返回：

  ```json
  {
      "code": 1,
      "data": {
          "uid": 514,
          "username": "dsa",
          "phone": "17557289510",
          "sex": 1,
          "address": null,
          "register_time": "2017-05-17 20:34:54",
          "avatar": "http://cdndevelop.jiumaojia.com/2017-06-13-16-25-45175?imageView2/2/w/100",
          "sinature": null
      }
  }
  ```



