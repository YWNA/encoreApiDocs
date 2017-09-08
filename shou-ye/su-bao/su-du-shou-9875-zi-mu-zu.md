* 接口地址：/news

* 版本号：1.4.2

* 提交方式：POST

* 接口参数：

  * category\_id：9

  * page：页码

  * page3：页码；若该字段不为空时则仅返回**Uper**主的用户数据。

  * page5：页码；若该字段不为空时则仅返回**字幕组**的用户数据。

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
                  }
              ],
              "category_banner_data": []
          }
      ]
  }
  ```



