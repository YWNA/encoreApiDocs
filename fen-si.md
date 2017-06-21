* 接口地址：/account/fans

* 提交方式：POST

* 接口参数：

  * page：页码

* 接口返回：

  ```json
  {
      "code": 1,
      "data": [
          {
              "account_id": 519,
              "follow_time": "2017-05-18 22:30:04",
              "username": "山田凉介的女朋友",
              "avatar": "http://onz6odc5j.bkt.clouddn.com/2017-05-17-20-51-07653?imageView2/2/w/100",
              "sinature": "哈哈",
              "is_close": 0 //是否互相关注
          },
          {
              "account_id": 491,
              "follow_time": "2017-04-20 18:28:01",
              "username": "鼹鼠不是硕鼠",
              "avatar": "http://onz6odc5j.bkt.clouddn.com/2017-05-10-19-57-02374?imageView2/2/w/100",
              "sinature": "",
              "is_close": 1
          }
      ]
  }
  ```



