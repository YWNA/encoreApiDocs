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
          "news_top_data": [],
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
              {
                  "post_id": 10447,
                  "title": "",
                  "content": "又是这种剧情 苏打酥 十元美",
                  "create_time": "1天前",
                  "read_num": 1,
                  "account_id": 60706,
                  "account_username": "婧文",
                  "account_avatar": "http://cdnsocial.jiumaojia.com/2017-09-11-09-28-23872?imageView2/2/w/100",
                  "comments_num": 0,
                  "praise_num": 1,
                  "if_praise": 0,
                  "is_save": 0,
                  "image": [
                      "http://cdnsocial.jiumaojia.com/FskvCuu1TwWuxOsjVfEijPRgy1jt",
                      "http://cdnsocial.jiumaojia.com/Ft3oHPFwNhKBMuIupsRhNtpAJnJ1",
                      "http://cdnsocial.jiumaojia.com/FrHMA27tYkwH50LUEw1AtAyTCDyM"
                  ],
                  "image_num": 3,
                  "banner_image": "http://cdnsocial.jiumaojia.com/FskvCuu1TwWuxOsjVfEijPRgy1jt"
              },
              {
                  "post_id": 10429,
                  "title": "",
                  "content": "自己选择，错了也要硬着头皮继续。\n明天开始我会努力让自己不再想起你，当然未来的日子里任何的意外也将与你无关了。\n明天去领证",
                  "create_time": "2天前",
                  "read_num": 4,
                  "account_id": 155632,
                  "account_username": "莫小优",
                  "account_avatar": "http://om4mfzope.bkt.clouddn.com/default_avatar.jpg?imageView2/2/w/100",
                  "comments_num": 0,
                  "praise_num": 0,
                  "if_praise": 0,
                  "is_save": 0,
                  "image": [],
                  "image_num": 0,
                  "banner_image": "http://cdnsocial.jiumaojia.com/default_avatar.jpg"
              },
              {
                  "post_id": 10400,
                  "title": "",
                  "content": "225596; ; ",
                  "create_time": "3天前",
                  "read_num": 10,
                  "account_id": 146536,
                  "account_username": "我微笑乛释怀伱給の伤",
                  "account_avatar": "http://cdnsocial.jiumaojia.com/1504166673563146536?imageView2/2/w/100",
                  "comments_num": 0,
                  "praise_num": 0,
                  "if_praise": 0,
                  "is_save": 0,
                  "image": [
                      "http://cdnsocial.jiumaojia.com/1505196066808146536",
                      "http://cdnsocial.jiumaojia.com/1505196066828146536"
                  ],
                  "image_num": 2,
                  "banner_image": "http://cdnsocial.jiumaojia.com/1505196066808146536"
              }
          ],
          "news_data": [],
          "newsr_data": [],
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
              {
                  "post_id": 10393,
                  "title": "",
                  "content": "来了来了",
                  "create_time": "4天前",
                  "read_num": 1,
                  "account_id": 155093,
                  "account_username": "爱仔俊俊毛",
                  "account_avatar": "http://cdnsocial.jiumaojia.com/2017-09-12-10-14-48737?imageView2/2/w/100",
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



