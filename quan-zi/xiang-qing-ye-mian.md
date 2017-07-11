* 接口地址：/section/detail

* 提交方式：POST

* 接口参数：

  * section\_id：圈子编号

  * page：页码（第一页的页码为1）

  * type：news或者post

  * sort：0为按时间排序，1为热度排序

* 接口返回：

  ```json
  {
      "code": 1,
      "data": {
          "section_id": 1,
          "name": "33Talk",
          "avatar": "http://om4mfzope.bkt.clouddn.com/2017-03-24-15-12-28840?imageView2/2/w/100",
          "description": "每日一发与众不同的日系文化观察",
          "account_id": 1,
          "is_follow": 0,
          "follow_num": 1,
          "post_data": [
              {
                  "post_id": 815,
                  "section_id": 1,
                  "content": "e",
                  "create_time": "2017-06-08 09:55:10",
                  "read_num": 0,
                  "account_id": 2839,
                  "account_username": "程序员",
                  "account_avatar": "http://cdndevelop.jiumaojia.com/2017-06-14-09-33-49865?imageView2/2/w/100",
                  "comments_num": 0,
                  "praise_num": 0,
                  "if_praise": 0,
                  "is_save": 0, //是否收藏
                  "is_manager": 0, //是否是圈主
                  "image": [
                      "http://cdndevelop.jiumaojia.com/2017-06-08-09-54-58526",
                      "http://cdndevelop.jiumaojia.com/2017-06-08-09-55-02160",
                      "http://cdndevelop.jiumaojia.com/2017-06-08-09-55-06778"
                  ]
              }
          ],
          "news_data": [
              {
                  "news_id": 258,
                  "title": "松山研一：“变色龙”的独特之道",
                  "content": "&nbsp;&nbsp;&nbsp;&nbsp;气质是一种说不清",
                  "category_id": 5,
                  "create_time": "2017-04-13 16:38:38",
                  "video_path": "",
                  "video_image": "",
                  "read_num": 175,
                  "section_id": 1,
                  "image": [
                      "http://cdndevelop.jiumaojia.com/2017-04-21-11-45-49546?imageView2/2/w/600"
                  ],
                  "source_image": "http://om4mfzope.bkt.clouddn.com/5_3.png",
                  "source_id": 5,
                  "account_data": {
                      "uid": 1,
                      "username": "33Talk",
                      "phone": 1,
                      "sex": 2,
                      "address": "",
                      "register_time": "2017-03-24 15:16:35",
                      "avatar": "http://om4mfzope.bkt.clouddn.com/2017-03-24-15-12-28840?imageView2/2/w/100",
                      "sinature": "AAAAB"
                  },
                  "type": "image",
                  "comments_num": 1,
                  "praise_num": 3,
                  "if_praise": 0
              }
          ],
          "weibo_data": [
              {
                  "weibo_name": "山下智久资讯台",
                  "weibo_path": "http://weibo.com/u/2132113514",
                  "weibo_avatar": "http://onz6odc5j.bkt.clouddn.com/2017-06-26-17-45-29795?imageView2/2/w/100"
              },
              {
                  "weibo_name": "Baidu山下智久吧 ",
                  "weibo_path": "http://weibo.com/baiduyamap?profile_ftype=1&amp;is_all=1#_0",
                  "weibo_avatar": "?imageView2/2/w/100"
              },
              {
                  "weibo_name": "芹菜香菜各种讨厌",
                  "weibo_path": "http://weibo.com/0409tomohisa?profile_ftype=1&amp;is_all=1#_0",
                  "weibo_avatar": "?imageView2/2/w/100"
              },
              {
                  "weibo_name": "Emma521_",
                  "weibo_path": "http://weibo.com/101198549?profile_ftype=1&amp;is_all=1#_0",
                  "weibo_avatar": "?imageView2/2/w/100"
              },
              {
                  "weibo_name": "Baidu山下智久吧",
                  "weibo_path": "http://weibo.com/baiduyamap",
                  "weibo_avatar": "http://onz6odc5j.bkt.clouddn.com/2017-06-26-17-48-10192?imageView2/2/w/100"
              },
              {
                  "weibo_name": "千叶的海论坛",
                  "weibo_path": "http://weibo.com/u/2679782074?profile_ftype=1&amp;is_all=1#_0",
                  "weibo_avatar": "http://onz6odc5j.bkt.clouddn.com/2017-06-26-17-48-10178?imageView2/2/w/100"
              },
              {
                  "weibo_name": "山下智久的恋久轩",
                  "weibo_path": "http://weibo.com/u/1932986501?profile_ftype=1&amp;is_all=1#_0",
                  "weibo_avatar": "http://onz6odc5j.bkt.clouddn.com/2017-06-26-17-48-10994?imageView2/2/w/100"
              }
          ]

      }
  }
  ```



