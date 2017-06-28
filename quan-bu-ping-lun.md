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
              "post_id": 1,
              "post_content": "我是第一个诶",
              "comment_content": "你好",
              "account_id": 514,
              "comment_time": "2017-05-18 20:56:29",
              "account_avatar": "http://cdnsocial.jiumaojia.com/2017-06-17-16-30-03463?imageView2/2/w/100",
              "account_username": "产品喵",
              "post_image": [
                  "http://cdndevelop.jiumaojia.com/2017-05-17-20-26-32115",
                  "http://cdndevelop.jiumaojia.com/2017-05-17-20-29-12787"
              ]
          },
          {
              "post_id": 1,
              "post_content": "我是第一个诶",
              "comment_content": "没有表情",
              "account_id": 509,
              "comment_time": "2017-05-18 13:09:14",
              "account_avatar": "http://onz6odc5j.bkt.clouddn.com/2017-05-18-12-43-26678?imageView2/2/w/100",
              "account_username": "零玖",
              "post_image": [
                  "http://cdndevelop.jiumaojia.com/2017-05-17-20-26-32115",
                  "http://cdndevelop.jiumaojia.com/2017-05-17-20-29-12787"
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



