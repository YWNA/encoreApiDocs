* 接口地址：/account/home

* 提交方式：POST

* 接口参数：

  1.account\_id：用户的编号

  2.page：页码

* 接口返回：

  ```json
  {
      "code": 1,
      "data": {
          "app_key": "egkmvwABFGOR",
          "app_value": "f5154eb045f679ebfaf1446a0de1a0ede6dc0449",
          "account_data": {
              "id": 2941,
              "username": "729_210801", //用户名
              "sex": 2, // 1为男生，0为女生，2为无
              "address": null,//用户地址
              "phone": "18142005882",//用户电话
              "register_time": "2017-06-12 11:08:29", //注册时间
              "email": "", //邮件地址
              "avatar": "http://om4mfzope.bkt.clouddn.com/default_avatar.jpg", //头像
              "sinature": null, //个人签名
              "country": null,//国家
              "pro": null,//省
              "area": null,//市
              "last_login_time": "2017-06-12 16:58:37",//最后登陆时间
              "serial_num": null,
              "poll_num_have": null,
              "index_trip_time": null,
              "getui_cid": null
          }
      }
  }
  ```



