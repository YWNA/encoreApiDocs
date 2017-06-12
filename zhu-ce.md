---
code: 1
data: 短信息发送成功
---

* 接口地址：`/register`
* 提交方式：POST
* 接口参数：

  * phone：用户的手机号码
  * code：手机验证码，若code值为空，则向phone手机号码发送注册验证码
  * password：用户的登录密码，密码必须是数字和字母，长度在6至16位

* 接口返回：

  * code值为空时

    ```json
    {
        "code": 1,
        "data": "短信息发送成功"
    }
    ```

  * code值不为空时

    ```json
    {
        "code": 1,
        "msg": "注册成功",
        "data": {
            "app_key": "aiqvyBFJOPU1",
            "app_value": "8be733bb6dad5c489c3fe475c437d627d2acc8f8"
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



