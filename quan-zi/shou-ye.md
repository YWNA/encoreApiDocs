接口地址：/section/index

* 提交方式：POST

* 接口参数：

  1.page：页码

* 接口返回：

  ```json
  {
      "code": 1,
      "data": {
          "banner_data": [
              {
                  "type": 1, //1、无反应2、跳转网页 3、跳转某个圈子主页 4、跳转某个资讯详情页  5、跳转某个帖子详情
                  "value": " ",
                  "image_path": "http://om4mfzope.bkt.clouddn.com/2017-03-27-10-22-34593"
              },
              {
                  "type": 2,
                  "value": "https://www.baidu.com/",
                  "image_path": "http://om4mfzope.bkt.clouddn.com/2017-03-27-11-05-45652"
              },
              {
                  "type": 3,
                  "value": 3,
                  "image_path": "http://om4mfzope.bkt.clouddn.com/2017-03-27-11-32-21869"
              }
          ],
          "section_follow_data": [
              {
                  "section_id": 145,
                  "name": "神木隆之介",
                  "avatar": "http://om4mfzope.bkt.clouddn.com/2017-03-27-10-11-36337"
              }
          ],
          "title_data": [
              {
                  "tid": 1,
                  "title": "a",
                  "avatar": "http://om4mfzope.bkt.clouddn.com/2017-03-27-10-26-01267"
              }
          ],
          "post_data": [
              {
                  "post_id": 836,
                  "content": "是",
                  "create_time": "2017-06-14 10:02:05",
                  "account_username": "刘大伟",
                  "account_avatar": "http://cdndevelop.jiumaojia.com/2017-06-14-09-33-49865?imageView2/2/w/100",
                  "account_id": 2839,
                  "comments_num": 0,
                  "praise_num": 1,
                  "if_praise": 1,
                  "image": [
                      "http://cdndevelop.jiumaojia.com/2017-06-14-10-01-51192",
                      "http://cdndevelop.jiumaojia.com/2017-06-14-10-01-57832"
                  ]
              },
              {
                  "post_id": 835,
                  "content": "Hvv",
                  "create_time": "2017-06-12 17:38:49",
                  "account_username": "刘大伟",
                  "account_avatar": "http://cdndevelop.jiumaojia.com/2017-06-14-09-33-49865?imageView2/2/w/100",
                  "account_id": 2839,
                  "comments_num": 3, //评论内容字段数据
                  "comments": {
                      "content": "wwwwwwwwwwwww",
                      "account_username": "刘大伟",
                      "account_avatar": "http://cdndevelop.jiumaojia.com/2017-06-14-09-33-49865"
                  },
                  "praise_num": 1,
                  "if_praise": 1,
                  "image": []
              }
          ]
      }
  }
  ```



