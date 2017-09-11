* 接口地址：/news

* 版本号：1.4.2

* 提交方式：POST

* 接口参数：

  * category\_id：3

  * page：页码；若该字段不为空时放回UPer主和字幕组的用户数据，还有页面下半部分速报资讯数据。

  * page3：页码；若该字段不为空时则仅返回**Uper**主的用户数据。

  * page5：页码；若该字段不为空时则仅返回**字幕组**的用户数据。

* 接口返回：

  ```json
  {
      "code": 1,
      "data": {
          "data3": [//UPer主数据
              {
                  "account_id": 491,
                  "account_username": "鼹鼠不是硕鼠",
                  "account_avatar": "http://onz6odc5j.bkt.clouddn.com/2017-05-10-19-57-02374?imageView2/2/w/100"
              },
              {
                  "account_id": 33546,
                  "account_username": "mikiiii酱",
                  "account_avatar": "http://cdnsocial.jiumaojia.com/2017-07-13-16-20-18593?imageView2/2/w/100"
              },
              {
                  "account_id": 492,
                  "account_username": "亚森罗宾",
                  "account_avatar": "http://onz6odc5j.bkt.clouddn.com/2017-05-03-09-25-20775?imageView2/2/w/100"
              }
          ],
          "data5": [//字幕组
              {
                  "account_id": 106699,
                  "account_username": "encore阿三",
                  "account_avatar": "http://cdnsocial.jiumaojia.com/2017-09-01-23-09-40243?imageView2/2/w/100"
              }
          ],
          "news_data": [//速报资讯
              {
                  "account_data": {
                      "account_id": 491,
                      "account_username": "鼹鼠不是硕鼠",
                      "account_avatar": "http://onz6odc5j.bkt.clouddn.com/2017-05-10-19-57-02374?imageView2/2/w/100"
                  },
                  "news_data": [
                      {
                          "news_id": 25635,
                          "account_id": 491,
                          "video_path": "1",
                          "video_image": "http://cdnsocial.jiumaojia.com/2017-08-12-16-29-24439",
                          "read_num": 4836,
                          "title": "警视厅搜查一课长 第2季",
                          "create_time": "9天前",
                          "classType": 22,
                          "class_type": 22,
                          "is_tv": 1,
                          "account_data": {
                              "uid": 491,
                              "username": "鼹鼠不是硕鼠",
                              "phone": 1,
                              "country": "",
                              "pro": "",
                              "area": "",
                              "sex": 1,
                              "address": "",
                              "register_time": "2017-04-11 15:22:04",
                              "avatar": "http://onz6odc5j.bkt.clouddn.com/2017-05-10-19-57-02374?imageView2/2/w/100",
                              "sinature": "",
                              "is_member": 0,
                              "label": 0,
                              "source_avatar": "http://onz6odc5j.bkt.clouddn.com/2017-05-10-19-57-02374",
                              "is_manager": 0
                          },
                          "image": [
                              "http://cdnsocial.jiumaojia.com/2017-08-12-16-29-20626?imageView2/2/w/600"
                          ],
                          "tv_num": 10,
                          "type": "video"
                      },
                      {
                          "news_id": 25563,
                          "account_id": 491,
                          "video_path": "111",
                          "video_image": "http://cdnsocial.jiumaojia.com/2017-08-11-13-34-35264",
                          "read_num": 8197,
                          "title": "爱情败犬向前冲",
                          "create_time": "9天前",
                          "classType": 22,
                          "class_type": 22,
                          "is_tv": 1,
                          "account_data": {
                              "uid": 491,
                              "username": "鼹鼠不是硕鼠",
                              "phone": 1,
                              "country": "",
                              "pro": "",
                              "area": "",
                              "sex": 1,
                              "address": "",
                              "register_time": "2017-04-11 15:22:04",
                              "avatar": "http://onz6odc5j.bkt.clouddn.com/2017-05-10-19-57-02374?imageView2/2/w/100",
                              "sinature": "",
                              "is_member": 0,
                              "label": 0,
                              "source_avatar": "http://onz6odc5j.bkt.clouddn.com/2017-05-10-19-57-02374",
                              "is_manager": 0
                          },
                          "image": [
                              "http://cdnsocial.jiumaojia.com/2017-08-11-13-34-26758?imageView2/2/w/600"
                          ],
                          "tv_num": 12,
                          "type": "video"
                      }
                  ]
              },
              {
                  "account_data": {
                      "account_id": 33546,
                      "account_username": "mikiiii酱",
                      "account_avatar": "http://cdnsocial.jiumaojia.com/2017-07-13-16-20-18593?imageView2/2/w/100"
                  },
                  "news_data": [
                      {
                          "news_id": 26992,
                          "account_id": 33546,
                          "video_path": "http://video.jiumaojia.com/001r3Au1jx07by3eUoJW010f11004nXo0k01.mp4",
                          "video_image": "http://cdnsocial.jiumaojia.com/2017-09-01-14-21-05587",
                          "read_num": 1941,
                          "title": "太贺和臼田麻美主演漫改电影「南瓜与美乃滋」预告片公开",
                          "create_time": "5天前",
                          "classType": 0,
                          "class_type": 0,
                          "is_tv": 0,
                          "account_data": {
                              "uid": 33546,
                              "username": "mikiiii酱",
                              "phone": "19900001694",
                              "country": "",
                              "pro": "",
                              "area": "",
                              "sex": 2,
                              "address": "",
                              "register_time": "2017-07-13 16:20:18",
                              "avatar": "http://cdnsocial.jiumaojia.com/2017-07-13-16-20-18593?imageView2/2/w/100",
                              "sinature": "",
                              "is_member": 1,
                              "label": 0,
                              "source_avatar": "http://cdnsocial.jiumaojia.com/2017-07-13-16-20-18593",
                              "is_manager": 0
                          },
                          "image": [
                              "http://cdnsocial.jiumaojia.com/2017-09-01-14-19-05796?imageView2/2/w/600"
                          ],
                          "type": "video"
                      },
                      {
                          "news_id": 26940,
                          "account_id": 33546,
                          "video_path": "",
                          "video_image": "",
                          "read_num": 6341,
                          "title": "元アイドリング队长远藤舞，将于年内从艺能界引退",
                          "create_time": "6天前",
                          "classType": 0,
                          "class_type": 0,
                          "is_tv": 0,
                          "account_data": {
                              "uid": 33546,
                              "username": "mikiiii酱",
                              "phone": "19900001694",
                              "country": "",
                              "pro": "",
                              "area": "",
                              "sex": 2,
                              "address": "",
                              "register_time": "2017-07-13 16:20:18",
                              "avatar": "http://cdnsocial.jiumaojia.com/2017-07-13-16-20-18593?imageView2/2/w/100",
                              "sinature": "",
                              "is_member": 1,
                              "label": 0,
                              "source_avatar": "http://cdnsocial.jiumaojia.com/2017-07-13-16-20-18593",
                              "is_manager": 0
                          },
                          "image": [
                              "http://cdnsocial.jiumaojia.com/2017-08-31-15-44-07659?imageView2/2/w/600"
                          ],
                          "type": "image"
                      }
                  ]
              },
              {
                  "account_data": {
                      "account_id": 492,
                      "account_username": "亚森罗宾",
                      "account_avatar": "http://onz6odc5j.bkt.clouddn.com/2017-05-03-09-25-20775?imageView2/2/w/100"
                  },
                  "news_data": [
                      {
                          "news_id": 25142,
                          "account_id": 492,
                          "video_path": "222",
                          "video_image": "http://cdnsocial.jiumaojia.com/2017-08-04-15-09-10638",
                          "read_num": 85557,
                          "title": "就是我们做的 更新至第8集",
                          "create_time": "6小时前",
                          "classType": 21,
                          "class_type": 21,
                          "is_tv": 1,
                          "account_data": {
                              "uid": 492,
                              "username": "亚森罗宾",
                              "phone": 1,
                              "country": "",
                              "pro": "",
                              "area": "",
                              "sex": 2,
                              "address": "",
                              "register_time": "2017-04-12 17:10:17",
                              "avatar": "http://onz6odc5j.bkt.clouddn.com/2017-05-03-09-25-20775?imageView2/2/w/100",
                              "sinature": "",
                              "is_member": 0,
                              "label": 0,
                              "source_avatar": "http://onz6odc5j.bkt.clouddn.com/2017-05-03-09-25-20775",
                              "is_manager": 0
                          },
                          "image": [
                              "http://cdnsocial.jiumaojia.com/2017-08-04-16-48-04598?imageView2/2/w/600"
                          ],
                          "tv_num": 8,
                          "type": "video"
                      }
                  ]
              }
          ]
      }
  }
  ```



