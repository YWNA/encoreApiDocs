* 接口地址：/account/home

* 提交方式：POST

* 接口参数：

  1.account\_id：用户的编号

  2.post\_\_page和news\_\_page

* 接口返回：

  ```json
  {
      "code": 1,
      "data": {
          "account_data": {
              "id": 30093,
              "username": "程序员",
              "phone": "18142005882",
              "sex": 2,
              "address": "",
              "register_time": "2017-06-12 17:19:26",
              "avatar": "http://cdnsocial.jiumaojia.com/150416418310230093?imageView2/2/w/100",
              "sinature": "encore",
              "is_follow": 0,
              "fans_num": 1,
              "follow_num": 3,
              "posts_num": 13,
              "news_num": 13,
              "role_data": []
          },
          "section_data": [
              {
                  "section_id": 18,
                  "section_name": "AKB48",
                  "section_avatar": "http://om4mfzope.bkt.clouddn.com/2017-03-27-10-33-36759"
              },
              {
                  "section_id": 423,
                  "section_name": "活动圈",
                  "section_avatar": "http://cdnsocial.jiumaojia.com/2017-07-06-15-13-58906"
              },
              {
                  "section_id": 516,
                  "section_name": "二宫和也",
                  "section_avatar": "http://om4mfzope.bkt.clouddn.com/2017-05-19-16-38-03728"
              },
              {
                  "section_id": 38,
                  "section_name": "石原里美",
                  "section_avatar": "http://om4mfzope.bkt.clouddn.com/2017-03-27-11-06-46358"
              },
              {
                  "section_id": 6,
                  "section_name": "岚",
                  "section_avatar": "http://om4mfzope.bkt.clouddn.com/2017-03-27-15-03-04482"
              },
              {
                  "section_id": 95,
                  "section_name": "小嶋阳菜",
                  "section_avatar": "http://om4mfzope.bkt.clouddn.com/2017-03-26-03-07-22666"
              },
              {
                  "section_id": 11,
                  "section_name": "山下智久",
                  "section_avatar": "http://cdnsocial.jiumaojia.com/2017-07-24-16-35-12932"
              },
              {
                  "section_id": 111,
                  "section_name": "新垣结衣",
                  "section_avatar": "http://om4mfzope.bkt.clouddn.com/2017-03-27-15-04-19121"
              }
          ],
          "news_data": [
              {
                  "news_id": 67,
                  "account_id": 30093,
                  "video_path": "",
                  "video_image": "",
                  "read_num": 5908,
                  "title": "【Encore pedia】生田斗真",
                  "create_time": "164天前",
                  "classType": 0,
                  "class_type": 0,
                  "is_tv": 0,
                  "account_data": {
                      "uid": 30093,
                      "username": "程序员",
                      "phone": "18142005882",
                      "country": "",
                      "pro": "",
                      "area": "",
                      "sex": 2,
                      "address": "",
                      "register_time": "2017-06-12 17:19:26",
                      "avatar": "http://cdnsocial.jiumaojia.com/150416418310230093?imageView2/2/w/100",
                      "sinature": "encore",
                      "is_member": 0,
                      "label": 0,
                      "source_avatar": "http://cdnsocial.jiumaojia.com/150416418310230093",
                      "is_manager": 0
                  },
                  "image": [
                      "http://cdnsocial.jiumaojia.com/default_avatar.jpg?imageView2/2/w/600"
                  ],
                  "type": "image"
              },
              {
                  "news_id": 64,
                  "account_id": 30093,
                  "video_path": "",
                  "video_image": "",
                  "read_num": 2601,
                  "title": "2017-樱花满开之预告",
                  "create_time": "164天前",
                  "classType": 0,
                  "class_type": 0,
                  "is_tv": 0,
                  "account_data": {
                      "uid": 30093,
                      "username": "程序员",
                      "phone": "18142005882",
                      "country": "",
                      "pro": "",
                      "area": "",
                      "sex": 2,
                      "address": "",
                      "register_time": "2017-06-12 17:19:26",
                      "avatar": "http://cdnsocial.jiumaojia.com/150416418310230093?imageView2/2/w/100",
                      "sinature": "encore",
                      "is_member": 0,
                      "label": 0,
                      "source_avatar": "http://cdnsocial.jiumaojia.com/150416418310230093",
                      "is_manager": 0
                  },
                  "image": [
                      "http://cdnsocial.jiumaojia.com/default_avatar.jpg?imageView2/2/w/600"
                  ],
                  "type": "image"
              }
          ],

          "post_data": [
              {
                  "post_id": 10397,
                  "title": "",
                  "content": "测试电文",
                  "content2": "a:2WD",//忽略本字段
                  "create_time": "20小时前",
                  "account_id": 30093,
                  "account_username": "程序员",
                  "account_avatar": "http://cdnsocial.jiumaojia.com/150416418310230093?imageView2/2/w/100",
                  "comments_num": 0,
                  "praise_num": 0,
                  "if_praise": 0,
                  "image": [
                      "http://cdnsocial.jiumaojia.com/FnxSmv14pGE1Ojn1um8dsrjJAQyB",
                      "http://cdnsocial.jiumaojia.com/Fh2e5mWKxp41f1OBgHmcoLe-u4NH"
                  ]
              },
              {
                  "post_id": 10392,
                  "title": "",
                  "content": "测试3",
                  "content2": "a:2:{i:0;a:1:{s:7:\"content\";s:7:\"测试3\";}i:1;a:1:{s:5:\"image\";s:59:\"http://cdnsocial.jiumaojia.com/FoLqNFtheHBWDajKO4d3IxVzKJF0\";}}",
                  "create_time": "23小时前",
                  "account_id": 30093,
                  "account_username": "程序员",
                  "account_avatar": "http://cdnsocial.jiumaojia.com/150416418310230093?imageView2/2/w/100",
                  "comments_num": 0,
                  "praise_num": 0,
                  "if_praise": 0,
                  "image": [
                      "http://cdnsocial.jiumaojia.com/FoLqNFtheHBWDajKO4d3IxVzKJF0"
                  ]
              },
              {
                  "post_id": 10391,
                  "title": "",
                  "content": "测试2",
                  "content2": "a:2WD",//忽略本字段
                  "create_time": "23小时前",
                  "account_id": 30093,
                  "account_username": "程序员",
                  "account_avatar": "http://cdnsocial.jiumaojia.com/150416418310230093?imageView2/2/w/100",
                  "comments_num": 0,
                  "praise_num": 0,
                  "if_praise": 0,
                  "image": []
              },
              {
                  "post_id": 10390,
                  "title": "",
                  "content": "测试",
                  "content2": "a:2:{i:0;a:1:{s:7:\"content\";s:6:\"测试\";}i:1;a:1:{s:5:\"image\";s:59:\"http://cdnsocial.jiumaojia.com/FtOZ9WRPjz_v7UHiNG7jlABbr1OV\";}}",
                  "create_time": "23小时前",
                  "account_id": 30093,
                  "account_username": "程序员",
                  "account_avatar": "http://cdnsocial.jiumaojia.com/150416418310230093?imageView2/2/w/100",
                  "comments_num": 0,
                  "praise_num": 0,
                  "if_praise": 0,
                  "image": []
              },
              {
                  "post_id": 10389,
                  "title": "",
                  "content": "测试",
                  "content2": "a:2:{i:0;a:1:{s:7:\"content\";s:6:\"测试\";}i:1;a:1:{s:5:\"image\";s:59:\"http://cdnsocial.jiumaojia.com/FtOZ9WRPjz_v7UHiNG7jlABbr1OV\";}}",
                  "create_time": "23小时前",
                  "account_id": 30093,
                  "account_username": "程序员",
                  "account_avatar": "http://cdnsocial.jiumaojia.com/150416418310230093?imageView2/2/w/100",
                  "comments_num": 0,
                  "praise_num": 0,
                  "if_praise": 0,
                  "image": []
              },
              {
                  "post_id": 10040,
                  "title": "",
                  "content": "哈哈啊哈哈啊哈啊哈啊",
                  "content2": null,
                  "create_time": "13天前",
                  "account_id": 30093,
                  "account_username": "程序员",
                  "account_avatar": "http://cdnsocial.jiumaojia.com/150416418310230093?imageView2/2/w/100",
                  "comments_num": 0,
                  "praise_num": 0,
                  "if_praise": 0,
                  "image": []
              },
              {
                  "post_id": 10037,
                  "title": "",
                  "content": "测试",
                  "content2": null,
                  "create_time": "13天前",
                  "account_id": 30093,
                  "account_username": "程序员",
                  "account_avatar": "http://cdnsocial.jiumaojia.com/150416418310230093?imageView2/2/w/100",
                  "comments_num": 0,
                  "praise_num": 0,
                  "if_praise": 0,
                  "image": [
                      "http://cdnsocial.jiumaojia.com/FtOZ9WRPjz_v7UHiNG7jlABbr1OV"
                  ]
              },
              {
                  "post_id": 10036,
                  "title": "",
                  "content": "测试",
                  "content2": null,
                  "create_time": "13天前",
                  "account_id": 30093,
                  "account_username": "程序员",
                  "account_avatar": "http://cdnsocial.jiumaojia.com/150416418310230093?imageView2/2/w/100",
                  "comments_num": 0,
                  "praise_num": 0,
                  "if_praise": 0,
                  "image": [
                      "http://cdnsocial.jiumaojia.com/FtOZ9WRPjz_v7UHiNG7jlABbr1OV"
                  ]
              }
          ]
      }
  }
  ```



