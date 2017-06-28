* 接口地址：/comments

* 提交方式：POST

* 接口参数：

  * page：页码
  * type：comments和reply，前者是评论，后者是评论的回复

* 接口返回：

* comments

* ```json
  {
      "code": 1,
      "data": [
          {
              "post_id": 26,
              "post_content": "米娜桑哦呀斯米⁽˙³˙⁾◟(๑•́ ₃ •̀๑)◞⁽˙³˙⁾",
              "comment_content": "苏打圈看到我团233",
              "account_id": 524,
              "comment_time": "2017-05-19 03:38:36",
              "account_avatar": "http://onz6odc5j.bkt.clouddn.com/2017-05-17-21-21-36297?imageView2/2/w/100",
              "account_username": "吐槽之神Vera",
              "post_image": [
                  "http://cdndevelop.jiumaojia.com/2017-05-17-22-55-01783"
              ]
          },
          {
              "post_id": 26,
              "post_content": "米娜桑哦呀斯米⁽˙³˙⁾◟(๑•́ ₃ •̀๑)◞⁽˙³˙⁾",
              "comment_content": "おやすみなさい",
              "account_id": 564,
              "comment_time": "2017-05-17 23:17:41",
              "account_avatar": "http://om4mfzope.bkt.clouddn.com/2017-05-30-23-06-37765?imageView2/2/w/100",
              "account_username": "李九原小可爱",
              "post_image": [
                  "http://cdndevelop.jiumaojia.com/2017-05-17-22-55-01783"
              ]
          }
      ]
  }
  ```

* reply
* ```json
  {
      "code": 1,
      "data": [
          {
              "post_id": 1,
              "comment_account_id": 488,
              "comment_content": "你好",
              "reply_account_id": 488,
              "reply_content": "dasda",
              "reply_comment_time": "2017-06-28 16:41:05",
              "comment_account_username": "Encore日娱酱",
              "comment_account_avatar": "http://onz6odc5j.bkt.clouddn.com/2017-05-11-13-47-47518?imageView2/2/w/100",
              "reply_account_username": "Encore日娱酱",
              "reply_account_avatar": "http://onz6odc5j.bkt.clouddn.com/2017-05-11-13-47-47518?imageView2/2/w/100",
              "post_content": "我是第一个诶",
              "post_image": [
                  "http://cdndevelop.jiumaojia.com/2017-05-17-20-26-32115?imageView2/2/w/100",
                  "http://cdndevelop.jiumaojia.com/2017-05-17-20-29-12787?imageView2/2/w/100"
              ]
          },
          {
              "post_id": 1,
              "comment_account_id": 488,
              "comment_content": "你好",
              "reply_account_id": 488,
              "reply_content": "测试的哦",
              "reply_comment_time": "2017-06-28 16:46:22",
              "comment_account_username": "Encore日娱酱",
              "comment_account_avatar": "http://onz6odc5j.bkt.clouddn.com/2017-05-11-13-47-47518?imageView2/2/w/100",
              "reply_account_username": "Encore日娱酱",
              "reply_account_avatar": "http://onz6odc5j.bkt.clouddn.com/2017-05-11-13-47-47518?imageView2/2/w/100",
              "post_content": "我是第一个诶",
              "post_image": [
                  "http://cdndevelop.jiumaojia.com/2017-05-17-20-26-32115?imageView2/2/w/100",
                  "http://cdndevelop.jiumaojia.com/2017-05-17-20-29-12787?imageView2/2/w/100"
              ]
          }
      ]
  }
  ```



