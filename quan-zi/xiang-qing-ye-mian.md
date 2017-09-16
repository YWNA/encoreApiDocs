* 接口地址：/section/detail

* 提交方式：POST

* 接口参数：

  * section\_id：圈子编号

  * page：页码（第一页的页码为1）

  * type：news\(速报资讯\)或者post\(动态帖子\)

  * sort：0为按时间排序，1为热度排序

* 接口返回：

  ```json
  {
      "code": 1,
      "data": {
          "section_data": {
              "section_id": 38,
              "name": "石原里美",
              "avatar": "http://om4mfzope.bkt.clouddn.com/2017-03-27-11-06-46358?imageView2/2/w/100",
              "description": "1986年12月24日出生于日本东京，演员",
              "account_id": 38,
              "is_follow": 1,
              "follow_num": 96110
          },   
          "post_top_data": [
              {
                  "post_id": 10464,
                  "title": "",
                  "content": "哈哈哈",
                  "create_time": "21小时前",
                  "read_num": 4,
                  "account_id": 29718,
                  "account_username": "我是小仙女",
                  "account_avatar": "http://cdnsocial.jiumaojia.com/2017-08-09-11-40-50646?imageView2/2/w/100",
                  "comments_num": 0,
                  "praise_num": 0,
                  "if_praise": 0,
                  "is_save": 0,
                  "image": [],
                  "image_num": 0,
                  "banner_image": "http://cdnsocial.jiumaojia.com/default_avatar.jpg"
              }
          ],
          "news_data": [
          {
                  "news_id": 27887,
                  "title": "朝5晚9~帅气和尚爱上我 01",
                  "content": "<p>【主要信息】\r\n导演: 平野真\r\n编剧: 相原实贵（原作） / 小山正太\r\n主演: 石原里美 / 山下智久 / 田中圭 / 高梨临 / 沙耶子 / 速水重道 / 古川雄辉 / 吉本实忧 / 长妻怜央 / 恒松祐里 / 寺田心 / 中村安奈 / 户田惠子 / 上島竜兵 / 小野武彦 / 加贺麻理子\r\n类型: 喜剧 / 爱情\r\n官方网站: blog.fujitv.co.jp/5ji9ji/\r\n首播: 2015-10-12\r\n\r\n\r\n【简介】\r\n一直梦想着去纽约工作的英语老师樱庭润子（石原里美饰），马上就要29岁了。虽然润子每天都为了梦想努力，但对于她来说，纽约还是一个很远很远的地方。在这种情况下，她也很久没有谈过恋爱了。有一天，在参加寺庙里举行的葬礼时，润子犯了一个大错误。因为脚麻了，所以她摇摇晃晃抓到了香炉的底座，并不可思议地将香灰倒在了正在诵经的和尚身上。润子心怀抱歉之意，某一天，突然想起了那个和尚。已经再也见不到了吧...正当润子这么想的时候，她被家人骗去参加相亲。相亲对象是毕业于东大的那个和尚，星川高岭（山下智久饰）。</p>",
                  "category_id": null,
                  "create_time": "18小时前",
                  "video_path": "http://aliyunvideo.jiumaojia.com/b9c3be33ac98481a9c31bcdca6805086/84c6b3e396374d53a52e30e0ad35de3c-5287d2089db37e62345123a1be272f8b.mp4",
                  "video_image": "http://cdnsocial.jiumaojia.com/2017-09-15-17-02-31846",
                  "read_num": 2390,
                  "account_id": 33740,
                  "label_id": 1,
                  "is_tv": 0,
                  "image": [
                      "http://cdnsocial.jiumaojia.com/2017-09-15-17-02-31846"
                  ],
                  "banner_image": "http://cdnsocial.jiumaojia.com/2017-09-15-17-02-31846",
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
                  "type": "video",
                  "comments_num": 0,
                  "praise_num": 0,
                  "is_store": 0,
                  "if_praise": 0
              }
          ],
          "newsr_data": [
              {
                  "news_id": 27885,
                  "title": "朝5晚9~帅气和尚爱上我",
                  "content": "",
                  "category_id": null,
                  "create_time": "18小时前",
                  "video_path": null,
                  "video_image": "http://cdnsocial.jiumaojia.com/2017-09-15-16-58-10436?imageView2/2/w/600",
                  "read_num": 532,
                  "account_id": 33740,
                  "label_id": 1,
                  "is_tv": 1,
                  "image": [
                      "http://cdnsocial.jiumaojia.com/2017-09-15-16-58-10436?imageView2/2/w/600"
                  ],
                  "banner_image": "http://cdnsocial.jiumaojia.com/2017-09-15-16-58-10436?imageView2/2/w/600",
                  "tv_num": 10,
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
                  }
          ],
          "post_data": [
              {
                  "post_id": 10464,
                  "title": "",
                  "content": "哈哈哈",
                  "create_time": "21小时前",
                  "read_num": 4,
                  "account_id": 29718,
                  "account_username": "我是小仙女",
                  "account_avatar": "http://cdnsocial.jiumaojia.com/2017-08-09-11-40-50646?imageView2/2/w/100",
                  "comments_num": 0,
                  "praise_num": 0,
                  "if_praise": 0,
                  "is_save": 0,
                  "image": [],
                  "image_num": 0,
                  "banner_image": "http://cdnsocial.jiumaojia.com/default_avatar.jpg",
                  "is_manager": 0
              }
          ],
          "api_description": "iOS端忽略news_top_data;Android端将news_top_data修改使用post_top_data字段"
      }
  }
  ```



