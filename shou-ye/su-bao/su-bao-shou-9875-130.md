* 本接口适用于
  1. 速报首页
  2. 速报首页中各个类别中的《更多》
  3. 速报首页4个类别后下滑刷新的数据（category\_id为1，即显示速报资讯类别下的数据即可）
  4. 上述两种情景下返回的数据格式一样
* 接口地址：/news

* 版本号：1.3.1

* 提交方式：POST

* 接口参数：

  * category\_id：非必填；1为速报资讯，2为资源，3为event，4为Encore号

  * page：非必填；页码（第一页的页码为1）

* 接口返回：

  ```json
  {
      "code": 1,
      "data": [
          [
              {
                  "news_id": "25072",
                  "account_id": "511",
                  "video_path": "http://video.jiumaojia.com/o_1bmh8d06qaub13nb1vbj1hp93qo9.mp4",
                  "video_image": "http://cdnsocial.jiumaojia.com/2017-08-02-18-29-06259",
                  "read_num": "3294",
                  "title": "小嶋阳菜CM：おぎやはぎ Web限定 DMMバヌーシー バヌメン、バヌジョ篇",
                  "create_time": "3天前",
                  "label_id": "3",
                  "account_data": {
                      "uid": "511",
                      "username": "咪报社",
                      "phone": "13532645938",
                      "country": "",
                      "pro": "",
                      "area": "",
                      "sex": "0",
                      "address": "",
                      "register_time": "2017-05-15 17:20:54",
                      "avatar": "http://cdnsocial.jiumaojia.com/2017-08-05-13-40-30820?imageView2/2/w/100",
                      "sinature": "sexy girl",
                      "is_member": "0",
                      "label": 0,
                      "is_manager": 0
                  },
                  "image": [
                      "http://cdnsocial.jiumaojia.com/2017-08-02-18-28-48117?imageView2/2/w/600"
                  ],
                  "type": "video"
              },
              {
                  "news_id": "25071",
                  "account_id": "91",
                  "read_num": "30030",
                  "title": "佐佐木希：雨が降ると君は優しい 虽然是很难的角色，日渐感受到了意义",
                  "create_time": "3天前",
                  "label_id": "8",
                  "account_data": {
                      "uid": "91",
                      "username": "佐佐木希",
                      "phone": 1,
                      "country": "",
                      "pro": "",
                      "area": "",
                      "sex": "2",
                      "address": "",
                      "register_time": "2017-03-24 07:16:43",
                      "avatar": "http://om4mfzope.bkt.clouddn.com/2017-03-26-03-32-43582?imageView2/2/w/100",
                      "sinature": "",
                      "is_member": "0",
                      "label": 0,
                      "is_manager": 0
                  },
                  "image": [
                      "http://cdnsocial.jiumaojia.com/2017-08-02-18-08-29713?imageView2/2/w/600",
                      "http://cdnsocial.jiumaojia.com/2017-08-02-18-08-30178?imageView2/2/w/600",
                      "http://cdnsocial.jiumaojia.com/2017-08-02-18-08-31886?imageView2/2/w/600"
                  ],
                  "type": "image"
              },
              {
                  "news_id": "25068",
                  "account_id": "102",
                  "read_num": "40768",
                  "title": "土屋太凤：哥哥太爱我了怎么办 系列图，哥哥的pose总是很新颖",
                  "create_time": "3天前",
                  "label_id": "8",
                  "account_data": {
                      "uid": "102",
                      "username": "土屋太凤",
                      "phone": 1,
                      "country": "",
                      "pro": "",
                      "area": "",
                      "sex": "2",
                      "address": "",
                      "register_time": "2017-03-24 07:16:43",
                      "avatar": "http://om4mfzope.bkt.clouddn.com/2017-03-26-03-26-04570?imageView2/2/w/100",
                      "sinature": "",
                      "is_member": "0",
                      "label": 0,
                      "is_manager": 0
                  },
                  "image": [
                      "http://cdnsocial.jiumaojia.com/2017-08-02-16-41-36814?imageView2/2/w/600",
                      "http://cdnsocial.jiumaojia.com/2017-08-02-16-41-36630?imageView2/2/w/600",
                      "http://cdnsocial.jiumaojia.com/2017-08-02-16-41-37900?imageView2/2/w/600"
                  ],
                  "type": "image"
              }
          ],
          [
              {
                  "news_id": "25191",
                  "account_id": "33546",
                  "read_num": "45954",
                  "title": "小松菜奈，对初共演的山崎贤人见面前的印象是？",
                  "create_time": "22小时前",
                  "label_id": "3",
                  "account_data": {
                      "uid": "33546",
                      "username": "mikiiii酱",
                      "phone": "19900001694",
                      "country": "",
                      "pro": "",
                      "area": "",
                      "sex": "2",
                      "address": "",
                      "register_time": "2017-07-13 16:20:18",
                      "avatar": "http://cdnsocial.jiumaojia.com/2017-07-13-16-20-18593?imageView2/2/w/100",
                      "sinature": "",
                      "is_member": "1",
                      "label": 0,
                      "is_manager": 0
                  },
                  "image": [
                      "http://cdnsocial.jiumaojia.com/2017-08-05-12-23-58894?imageView2/2/w/600"
                  ],
                  "type": "image"
              },
              {
                  "news_id": "25189",
                  "account_id": "33546",
                  "read_num": "27987",
                  "title": "贺来贤人对荣仓奈奈的求婚密语揭晓「是认真的吗?」「认真的」",
                  "create_time": "1天前",
                  "label_id": "3",
                  "account_data": {
                      "uid": "33546",
                      "username": "mikiiii酱",
                      "phone": "19900001694",
                      "country": "",
                      "pro": "",
                      "area": "",
                      "sex": "2",
                      "address": "",
                      "register_time": "2017-07-13 16:20:18",
                      "avatar": "http://cdnsocial.jiumaojia.com/2017-07-13-16-20-18593?imageView2/2/w/100",
                      "sinature": "",
                      "is_member": "1",
                      "label": 0,
                      "is_manager": 0
                  },
                  "image": [
                      "http://cdnsocial.jiumaojia.com/2017-08-05-11-38-49992?imageView2/2/w/600"
                  ],
                  "type": "image"
              },
              {
                  "news_id": "25185",
                  "account_id": "511",
                  "video_path": "http://video.jiumaojia.com/o_1bmmqj17c1hbr1qjmvrmi9l5en9.mp4",
                  "video_image": "http://cdnsocial.jiumaojia.com/2017-08-04-22-23-47548",
                  "read_num": "11658",
                  "title": "坂口健太郎CM：ツタヤ トーンモバイル  空気を読まずにプロポーズ篇",
                  "create_time": "1天前",
                  "label_id": "3",
                  "account_data": {
                      "uid": "511",
                      "username": "咪报社",
                      "phone": "13532645938",
                      "country": "",
                      "pro": "",
                      "area": "",
                      "sex": "0",
                      "address": "",
                      "register_time": "2017-05-15 17:20:54",
                      "avatar": "http://cdnsocial.jiumaojia.com/2017-08-05-13-40-30820?imageView2/2/w/100",
                      "sinature": "sexy girl",
                      "is_member": "0",
                      "label": 0,
                      "is_manager": 0
                  },
                  "image": [
                      "http://cdnsocial.jiumaojia.com/2017-08-04-22-23-09818?imageView2/2/w/600"
                  ],
                  "type": "video"
              }
          ],
          [
              {
                  "news_id": "25188",
                  "account_id": "33546",
                  "video_path": "http://video.jiumaojia.com/002ZCLXrlx07dbXkzXcs010f0100eteX0k01.mp4",
                  "video_image": "http://cdnsocial.jiumaojia.com/2017-08-05-11-17-28461",
                  "read_num": "9776",
                  "title": "SexyZone菊池风磨solo live「風 is I？」这么帅气你还是我认识的磨宝吗？",
                  "create_time": "1天前",
                  "label_id": "3",
                  "account_data": {
                      "uid": "33546",
                      "username": "mikiiii酱",
                      "phone": "19900001694",
                      "country": "",
                      "pro": "",
                      "area": "",
                      "sex": "2",
                      "address": "",
                      "register_time": "2017-07-13 16:20:18",
                      "avatar": "http://cdnsocial.jiumaojia.com/2017-07-13-16-20-18593?imageView2/2/w/100",
                      "sinature": "",
                      "is_member": "1",
                      "label": 0,
                      "is_manager": 0
                  },
                  "image": [
                      "http://cdnsocial.jiumaojia.com/default_avatar.jpg?imageView2/2/w/600"
                  ],
                  "type": "video"
              },
              {
                  "news_id": "25186",
                  "account_id": "804",
                  "read_num": "184358",
                  "title": "片寄凉太：8月25日(周五)，为了答谢和见一见一直给予我支持的中国粉丝们，我将在上海举办个人见面会！",
                  "create_time": "1天前",
                  "label_id": "8",
                  "account_data": {
                      "uid": "804",
                      "username": "片寄凉太",
                      "phone": 1,
                      "country": "",
                      "pro": "",
                      "area": "",
                      "sex": "2",
                      "address": "",
                      "register_time": "2017-05-23 16:28:39",
                      "avatar": "http://om4mfzope.bkt.clouddn.com/default_avatar.jpg?imageView2/2/w/100",
                      "sinature": "",
                      "is_member": "0",
                      "label": 0,
                      "is_manager": 0
                  },
                  "image": [
                      "http://cdnsocial.jiumaojia.com/2017-08-04-22-32-11207?imageView2/2/w/600"
                  ],
                  "type": "image"
              },
              {
                  "news_id": "25184",
                  "account_id": "33546",
                  "video_path": "http://video.jiumaojia.com/%E5%9C%9F%E5%B1%8B%E5%A4%AA%E9%B3%B3%20%E3%80%8EFe%CC%81licies%E3%80%8F.mp4",
                  "video_image": "http://cdnsocial.jiumaojia.com/2017-08-04-21-48-22113",
                  "read_num": "15410",
                  "title": "土屋太鳳凤演唱「Felicies」主題歌配信开始，MV也公开",
                  "create_time": "1天前",
                  "label_id": "3",
                  "account_data": {
                      "uid": "33546",
                      "username": "mikiiii酱",
                      "phone": "19900001694",
                      "country": "",
                      "pro": "",
                      "area": "",
                      "sex": "2",
                      "address": "",
                      "register_time": "2017-07-13 16:20:18",
                      "avatar": "http://cdnsocial.jiumaojia.com/2017-07-13-16-20-18593?imageView2/2/w/100",
                      "sinature": "",
                      "is_member": "1",
                      "label": 0,
                      "is_manager": 0
                  },
                  "image": [
                      "http://cdnsocial.jiumaojia.com/default_avatar.jpg?imageView2/2/w/600"
                  ],
                  "type": "video"
              }
          ],
          [
              {
                  "news_id": "25183",
                  "account_id": "488",
                  "read_num": "634356",
                  "title": "【重大告知】Encore 1.2.2 新版使用攻略！",
                  "create_time": "1天前",
                  "label_id": "1",
                  "account_data": {
                      "uid": "488",
                      "username": "Encore日娱酱",
                      "phone": 1,
                      "country": "",
                      "pro": "",
                      "area": "",
                      "sex": "1",
                      "address": "",
                      "register_time": "2017-04-10 15:26:08",
                      "avatar": "http://onz6odc5j.bkt.clouddn.com/2017-05-11-13-47-47518?imageView2/2/w/100",
                      "sinature": "",
                      "is_member": "1",
                      "label": 0,
                      "is_manager": 0
                  },
                  "image": [
                      "http://cdnsocial.jiumaojia.com/2017-08-04-20-07-34716?imageView2/2/w/600"
                  ],
                  "type": "image"
              },
              {
                  "news_id": "25187",
                  "account_id": "33546",
                  "read_num": "14258",
                  "title": "北川景子恐怖初挑战「鬼屋绝对不回去」与志尊淳&和川栄李奈共演",
                  "create_time": "1天前",
                  "label_id": "3",
                  "account_data": {
                      "uid": "33546",
                      "username": "mikiiii酱",
                      "phone": "19900001694",
                      "country": "",
                      "pro": "",
                      "area": "",
                      "sex": "2",
                      "address": "",
                      "register_time": "2017-07-13 16:20:18",
                      "avatar": "http://cdnsocial.jiumaojia.com/2017-07-13-16-20-18593?imageView2/2/w/100",
                      "sinature": "",
                      "is_member": "1",
                      "label": 0,
                      "is_manager": 0
                  },
                  "image": [
                      "http://cdnsocial.jiumaojia.com/2017-08-05-11-08-18765?imageView2/2/w/600"
                  ],
                  "type": "image"
              },
              {
                  "news_id": "25182",
                  "account_id": "33546",
                  "video_path": "http://video.jiumaojia.com/001ZUXv2lx07dbao5k9W010f01009rhW0k01.mp4",
                  "video_image": "http://cdnsocial.jiumaojia.com/2017-08-04-20-05-14635",
                  "read_num": "11901",
                  "title": "乃木坂46新单「逃げ水」初回盤的特典映像公开 ，「乃木恋リアル」等收录",
                  "create_time": "1天前",
                  "label_id": "3",
                  "account_data": {
                      "uid": "33546",
                      "username": "mikiiii酱",
                      "phone": "19900001694",
                      "country": "",
                      "pro": "",
                      "area": "",
                      "sex": "2",
                      "address": "",
                      "register_time": "2017-07-13 16:20:18",
                      "avatar": "http://cdnsocial.jiumaojia.com/2017-07-13-16-20-18593?imageView2/2/w/100",
                      "sinature": "",
                      "is_member": "1",
                      "label": 0,
                      "is_manager": 0
                  },
                  "image": [
                      "http://cdnsocial.jiumaojia.com/default_avatar.jpg?imageView2/2/w/600"
                  ],
                  "type": "video"
              }
          ]
      ]
  }
  ```



