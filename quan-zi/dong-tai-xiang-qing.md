* 接口地址：/post/detail

* 提交方式：POST

* 接口参数：

  * post\_id：动态编号（帖子）

  * page：页码

* 接口返回：

  ```json
  {
      "code": 1,
      "data": {
          "post_id": 11,
          "content": "来个可爱的小锦鲤~",
          "read_num": 11,
          "account_avatar": "http://onz6odc5j.bkt.clouddn.com/2017-05-17-22-19-58204?imageView2/2/w/100",
          "account_name": "涼介大好きのイチゴ！",
          "if_praise": 0,
          "images": [
              "http://cdndevelop.jiumaojia.com/2017-05-17-22-16-21321?imageView2/2/w/800"
          ],
          "comments": [
              {
                  "comment_id": 9,
                  "content": "转发比锦鲤，接下来一年32小天使将顺顺利利开开心心~哈哈",
                  "comment_time": "2017-05-17 22:31:11",
                  "account_username": "山田凉介的女朋友",
                  "account_avatar": "http://onz6odc5j.bkt.clouddn.com/2017-05-17-20-51-07653?imageView2/2/w/100",
                  "account_id": 519,
                  "comment_comment": []
              }
          ],
          "comments_num": 1,
          "praise_account": [
              {
                  "account_id": 519,
                  "account_username": "山田凉介的女朋友",
                  "account_avatar": "http://onz6odc5j.bkt.clouddn.com/2017-05-17-20-51-07653?imageView2/2/w/100"
              },
              {
                  "account_id": 544,
                  "account_username": "小白团子",
                  "account_avatar": "http://onz6odc5j.bkt.clouddn.com/2017-05-17-21-01-32221?imageView2/2/w/100"
              },
              {
                  "account_id": 773,
                  "account_username": "strawberry",
                  "account_avatar": "http://om4mfzope.bkt.clouddn.com/2017-05-19-15-59-49572?imageView2/2/w/100"
              }
          ],
          "praise_num": 3
      }
  }
  ```



