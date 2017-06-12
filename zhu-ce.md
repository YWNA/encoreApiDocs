---
code: 1
data: 短信息发送成功
---

接口地址：`/V001/register`

* 提交方式：POST
* 接口参数：

  * phone：用户的手机号码

  * code：手机验证码，若code值为空，则向phone手机号码发送注册验证码

* 接口返回：

  * code值为空时

    \`{"code":1,"data":"\u77ed\u4fe1\u606f\u53d1\u9001\u6210\u529f"}\`

  * code值不为空时  
    `{`

    `"code": 1,`

    `"msg": "注册成功",`

    `"data": {`

    `"app_key": "aiqvyBFJOPU1",`

    `"app_value": "8be733bb6dad5c489c3fe475c437d627d2acc8f8"`

    `}`

    `}`



