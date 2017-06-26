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
          "uid": 544,
          "username": "小白团子",
          "phone": "18399563090",
          "sex": 0,
          "address": "",
          "register_time": "2017-05-17 20:58:29",
          "avatar": "http://onz6odc5j.bkt.clouddn.com/2017-05-17-21-01-32221?imageView2/2/w/100",
          "sinature": "",
          "is_own": 0,
          "is_follow": 0,
          "fans_num": 2,
          "follow_num": 2,
          "posts_num": 1,
          "posts": [
              {
                  "post_id": 1562,
                  "section_id": 180,
                  "content": "打个卡试试",
                  "create_time": "2017-06-24 17:37:49",
                  "read_num": 2,
                  "account_id": 31611,
                  "account_username": "栗欲熏心",
                  "account_avatar": "http://om4mfzope.bkt.clouddn.com/default_avatar.jpg?imageView2/2/w/100",
                  "comments_num": 0,
                  "praise_num": 0,
                  "if_praise": 0,
                  "image": [
                      "http://cdnsocial.jiumaojia.com/2017-06-24-17-37-41970"
                  ]
              }
          ],
          "posts_num": 21
          "sections": [
              {
                  "section_id": 10,
                  "section_name": "KAT-TUN",
                  "section_avatar": "http://om4mfzope.bkt.clouddn.com/2017-03-27-10-15-15383?imageView2/2/w/100"
              },
              {
                  "section_id": 111,
                  "section_name": "新垣结衣",
                  "section_avatar": "http://om4mfzope.bkt.clouddn.com/2017-03-27-15-04-19121?imageView2/2/w/100"
              }
              {
                  "section_id": 11,
                  "section_name": "山下智久",
                  "section_avatar": "http://om4mfzope.bkt.clouddn.com/2017-03-27-10-17-18189?imageView2/2/w/100"
              }
          ],
          "sections_num": 64
      }
  }
  ```



