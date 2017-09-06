* 本接口适用于
  1. 速报首页
  2. 速报首页中各个类别中的《更多》
  3. 速报首页4个类别后下滑刷新的数据（category\_id为1，即显示速报资讯类别下的数据即可）
  4. 上述两种情景下返回的数据格式一样
* 接口地址：/news

* 版本号：1.4.2

* 提交方式：POST

* 接口参数：

  * category\_id：非必填；1为速报资讯，2为资源，3为剧评，5为周边，7为扩列，9字幕组

  * category\_\_category\_\_id：

  * page：非必填；页码（第一页的页码为1）

  * play\_date：非必填；上映日期，1.周一2.周二------7周日，8为17年，9为16年，10为更久

* 接口返回：

  ```json
  {
      "code": 1,
      "data": [
          {
              "category_id": 1,
              "category_data": [
                  {
                      "news_id": 27221,
                      "account_id": 106699,
                      "video_path": "",
                      "video_image": "",
                      "read_num": 11510,
                      "title": "生田斗真主演 《人生密密缝》（他们认真编织的时候）剧情简介",
                      "create_time": "3小时前",
                      "classType": 0,
                      "class_type": 0,
                      "account_data": {
                          "uid": 106699,
                          "username": "encore阿三",
                          "phone": "9082648891",
                          "country": "",
                          "pro": "",
                          "area": "",
                          "sex": 0,
                          "address": "",
                          "register_time": "2017-08-11 13:27:12",
                          "avatar": "http://cdnsocial.jiumaojia.com/2017-09-01-23-09-40243?imageView2/2/w/100",
                          "sinature": "",
                          "is_member": 0,
                          "label": 0,
                          "source_avatar": "http://cdnsocial.jiumaojia.com/2017-09-01-23-09-40243",
                          "is_manager": 0
                      },
                      "image": [
                          "http://cdnsocial.jiumaojia.com/2017-09-06-09-52-46707?imageView2/2/w/600"
                      ],
                      "type": "image"
                  }
              ],
              "category_banner_data": [] //banner数据
          },
          {
              "category_id": 3,
              "category_data": [
                  {
                      "news_id": 27221,
                      "account_id": 106699,
                      "video_path": "",
                      "video_image": "",
                      "read_num": 11510,
                      "title": "生田斗真主演 《人生密密缝》（他们认真编织的时候）剧情简介",
                      "create_time": "3小时前",
                      "classType": 0,
                      "class_type": 0,
                      "account_data": {
                          "uid": 106699,
                          "username": "encore阿三",
                          "phone": "9082648891",
                          "country": "",
                          "pro": "",
                          "area": "",
                          "sex": 0,
                          "address": "",
                          "register_time": "2017-08-11 13:27:12",
                          "avatar": "http://cdnsocial.jiumaojia.com/2017-09-01-23-09-40243?imageView2/2/w/100",
                          "sinature": "",
                          "is_member": 0,
                          "label": 0,
                          "source_avatar": "http://cdnsocial.jiumaojia.com/2017-09-01-23-09-40243",
                          "is_manager": 0
                      },
                      "image": [
                          "http://cdnsocial.jiumaojia.com/2017-09-06-09-52-46707?imageView2/2/w/600"
                      ],
                      "type": "image"
                  },
                  {
                      "news_id": 27213,
                      "account_id": 259,
                      "video_path": "",
                      "video_image": "",
                      "read_num": 1853,
                      "title": "玉城Tina：真的“yagitama”",
                      "create_time": "14小时前",
                      "classType": 0,
                      "class_type": 0,
                      "account_data": {
                          "uid": 259,
                          "username": "玉城Tina",
                          "phone": 1,
                          "country": "",
                          "pro": "",
                          "area": "",
                          "sex": 2,
                          "address": "",
                          "register_time": "2017-03-24 07:16:43",
                          "avatar": "http://om4mfzope.bkt.clouddn.com/2017-03-27-15-07-25744?imageView2/2/w/100",
                          "sinature": "",
                          "is_member": 0,
                          "label": 0,
                          "source_avatar": "http://om4mfzope.bkt.clouddn.com/2017-03-27-15-07-25744",
                          "is_manager": 0
                      },
                      "image": [
                          "http://cdnsocial.jiumaojia.com/2017-09-05-23-18-09457?imageView2/2/w/600"
                      ],
                      "type": "image"
                  },
                  {
                      "news_id": 27208,
                      "account_id": 90,
                      "video_path": "",
                      "video_image": "",
                      "read_num": 3694,
                      "title": "永野芽郁：《是我们做的》第八话，应该是很有冲击性的",
                      "create_time": "15小时前",
                      "classType": 0,
                      "class_type": 0,
                      "account_data": {
                          "uid": 90,
                          "username": "永野芽郁",
                          "phone": 1,
                          "country": "",
                          "pro": "",
                          "area": "",
                          "sex": 2,
                          "address": "",
                          "register_time": "2017-03-24 07:16:43",
                          "avatar": "http://om4mfzope.bkt.clouddn.com/2017-03-26-02-53-26705?imageView2/2/w/100",
                          "sinature": "",
                          "is_member": 0,
                          "label": 0,
                          "source_avatar": "http://om4mfzope.bkt.clouddn.com/2017-03-26-02-53-26705",
                          "is_manager": 0
                      },
                      "image": [
                          "http://cdnsocial.jiumaojia.com/2017-09-05-22-10-45617?imageView2/2/w/600"
                      ],
                      "type": "image"
                  }
              ],
              "category_banner_data": []
          },
          {
              "category_id": 2,
              "category_data": [
                  {
                      "news_id": 27164,
                      "account_id": 33740,
                      "video_path": "22",
                      "video_image": "",
                      "read_num": 1567,
                      "title": "99.9-刑事专门律师",
                      "create_time": "1天前",
                      "classType": 22,
                      "class_type": 22,
                      "account_data": {
                          "uid": 33740,
                          "username": "猪猪字幕组",
                          "phone": "19900004819",
                          "country": "",
                          "pro": "",
                          "area": "",
                          "sex": 2,
                          "address": "",
                          "register_time": "2017-07-14 14:41:06",
                          "avatar": "http://cdnsocial.jiumaojia.com/2017-07-14-14-41-06488?imageView2/2/w/100",
                          "sinature": "",
                          "is_member": 1,
                          "label": 1,
                          "source_avatar": "http://cdnsocial.jiumaojia.com/2017-07-14-14-41-06488",
                          "is_manager": 1
                      },
                      "image": [
                          "http://cdnsocial.jiumaojia.com/default_avatar.jpg?imageView2/2/w/600"
                      ],
                      "tv_num": 9,
                      "type": "video"
                  },
                  {
                      "news_id": 26992,
                      "account_id": 33546,
                      "video_path": "http://video.jiumaojia.com/001r3Au1jx07by3eUoJW010f11004nXo0k01.mp4",
                      "video_image": "http://cdnsocial.jiumaojia.com/2017-09-01-14-21-05587",
                      "read_num": 1790,
                      "title": "太贺和臼田麻美主演漫改电影「南瓜与美乃滋」预告片公开",
                      "create_time": "4天前",
                      "classType": 0,
                      "class_type": 0,
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
                  }
              ],
              "category_banner_data": [
                  {
                      "type": 2,
                      "value": 2,
                      "image_path": "http://cdnsocial.jiumaojia.com/2017-08-29-17-52-50109",
                      "video_path": "",
                      "url": "http://appp.jiumaojia.com/Home/Tv/ac",
                      "news_id": null
                  },
                  {
                      "type": 2,
                      "value": 2,
                      "image_path": "http://cdnsocial.jiumaojia.com/2017-08-29-17-52-12257",
                      "video_path": "",
                      "url": "http://appp.jiumaojia.com/Home/Tv/ac",
                      "news_id": null
                  }
              ]
          },
          {
              "category_id": 5,
              "category_data": [
                  {
                      "id": 1,
                      "title": "测试1内容2017-09-06 13:51:12"
                  },
                  {
                      "id": 2,
                      "title": "测试2内容2017-09-06 13:51:12"
                  },
                  {
                      "id": 3,
                      "title": "测试3内容2017-09-06 13:51:12"
                  },
                  {
                      "id": 4,
                      "title": "测试4内容2017-09-06 13:51:12"
                  }
              ],
              "category_banner_data": []
          },
          {
              "category_id": 7,
              "category_data": [
                  {
                      "id": 1,
                      "title": "测试1内容2017-09-06 13:51:12"
                  },
                  {
                      "id": 2,
                      "title": "测试2内容2017-09-06 13:51:12"
                  },
                  {
                      "id": 3,
                      "title": "测试3内容2017-09-06 13:51:12"
                  },
                  {
                      "id": 4,
                      "title": "测试4内容2017-09-06 13:51:12"
                  }
              ],
              "category_banner_data": []
          },
          {
              "category_id": 9,
              "category_data": [
                  {
                      "news_id": 27221,
                      "account_id": 106699,
                      "video_path": "",
                      "video_image": "",
                      "read_num": 11510,
                      "title": "生田斗真主演 《人生密密缝》（他们认真编织的时候）剧情简介",
                      "create_time": "3小时前",
                      "classType": 0,
                      "class_type": 0,
                      "account_data": {
                          "uid": 106699,
                          "username": "encore阿三",
                          "phone": "9082648891",
                          "country": "",
                          "pro": "",
                          "area": "",
                          "sex": 0,
                          "address": "",
                          "register_time": "2017-08-11 13:27:12",
                          "avatar": "http://cdnsocial.jiumaojia.com/2017-09-01-23-09-40243?imageView2/2/w/100",
                          "sinature": "",
                          "is_member": 0,
                          "label": 0,
                          "source_avatar": "http://cdnsocial.jiumaojia.com/2017-09-01-23-09-40243",
                          "is_manager": 0
                      },
                      "image": [
                          "http://cdnsocial.jiumaojia.com/2017-09-06-09-52-46707?imageView2/2/w/600"
                      ],
                      "type": "image"
                  },
                  {
                      "news_id": 27213,
                      "account_id": 259,
                      "video_path": "",
                      "video_image": "",
                      "read_num": 1853,
                      "title": "玉城Tina：真的“yagitama”",
                      "create_time": "14小时前",
                      "classType": 0,
                      "class_type": 0,
                      "account_data": {
                          "uid": 259,
                          "username": "玉城Tina",
                          "phone": 1,
                          "country": "",
                          "pro": "",
                          "area": "",
                          "sex": 2,
                          "address": "",
                          "register_time": "2017-03-24 07:16:43",
                          "avatar": "http://om4mfzope.bkt.clouddn.com/2017-03-27-15-07-25744?imageView2/2/w/100",
                          "sinature": "",
                          "is_member": 0,
                          "label": 0,
                          "source_avatar": "http://om4mfzope.bkt.clouddn.com/2017-03-27-15-07-25744",
                          "is_manager": 0
                      },
                      "image": [
                          "http://cdnsocial.jiumaojia.com/2017-09-05-23-18-09457?imageView2/2/w/600"
                      ],
                      "type": "image"
                  },
                  {
                      "news_id": 26940,
                      "account_id": 33546,
                      "video_path": "",
                      "video_image": "",
                      "read_num": 6110,
                      "title": "元アイドリング队长远藤舞，将于年内从艺能界引退",
                      "create_time": "5天前",
                      "classType": 0,
                      "class_type": 0,
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
              ],
              "category_banner_data": []
          }
      ]
  }
  ```



