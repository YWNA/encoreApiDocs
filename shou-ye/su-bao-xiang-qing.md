* 接口地址：/news/detail

* 提交方式：POST

* 接口参数：

  * news\_id：速报资讯编号

  * page：页码（第一页的页码为1）

* 接口返回：

  ```json
  {
      "code": 1,
      "data": {
          "news_id": 154,
          "title": "东京地铁CM的几张截图~",
          "content": [
              {
                  "type": "text",
                  "value": "第一段"
              },
              {
                  "type": "image",
                  "value": "http://om4mfzope.bkt.clouddn.com/2017-03-27-10-55-18115",
                  "image_info": {
                      "size": 219458,
                      "format": "jpeg",
                      "width": 1600,
                      "height": 1066,
                      "colorModel": "ycbcr"
                  }
              },
              {
                  "type": "text",
                  "value": "第二段"
              }
          ],
          "category_id": 5,
          "create_time": "2017-04-01 16:08:00",
          "is_translate": 1, //1为支持，0为不支持
          "account_avatar": "http://om4mfzope.bkt.clouddn.com/2017-03-27-11-06-46358?imageView2/2/w/100",//用户头像
          "account_name": "石原里美",//用户名
          "banner_image": "http://om4mfzope.bkt.clouddn.com/2017-03-27-10-32-25564", //页面顶部封面图片，若结果中字段video_path有值则为视屏的封面图片
          "source_image": "http://om4mfzope.bkt.clouddn.com/5_3.png", //来源图片
          "comments": [
              {
                  "comment_id": 468,
                  "content": "21",
                  "comment_time": "2017-06-19 19:58:08",
                  "account_username": "Encore日娱酱",
                  "account_avatar": "http://onz6odc5j.bkt.clouddn.com/2017-05-11-13-47-47518?imageView2/2/w/100",
                  "account_id": 488,
                  "comment_comment": [
                      {
                          "id": 470,
                          "content": "23",
                          "comment_time": "2017-06-20 11:32:13",
                          "account_id": 2839,
                          "news_id": 20187,
                          "at_account_id": 2839,
                          "comment_id": 468,
                          "comment_id_p": 468,
                          "account_username": "刘大伟",
                          "account_avatar": "http://cdndevelop.jiumaojia.com/2017-06-14-09-33-49865?imageView2/2/w/100",
                          "at_account_username": "刘大伟",
                          "at_account_avatar": "http://cdndevelop.jiumaojia.com/2017-06-14-09-33-49865?imageView2/2/w/100",
                          "is_show_at": 1
                      },
                      {
                          "id": 469,
                          "content": "22",
                          "comment_time": "2017-06-20 11:30:17",
                          "account_id": 2839,
                          "news_id": 20187,
                          "at_account_id": 488,
                          "comment_id": 468,
                          "comment_id_p": 0,
                          "account_username": "刘大伟",
                          "account_avatar": "http://cdndevelop.jiumaojia.com/2017-06-14-09-33-49865?imageView2/2/w/100",
                          "at_account_username": "Encore日娱酱",
                          "at_account_avatar": "http://onz6odc5j.bkt.clouddn.com/2017-05-11-13-47-47518?imageView2/2/w/100",
                          "is_show_at": 0
                      }
                  ]
              }
          ],
          "comments_num": 1,
          "if_praise": 0,
          "praise_account": [{
                  "account_id": 490,
                  "account_username": "Encore小可爱",
                  "account_avatar": "http://onz6odc5j.bkt.clouddn.com/2017-05-10-19-58-08194?imageView2/2/w/100"
              }],
          "praise_num": 0
      }
  }
  ```



