接口地址：/news/detail

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
                  "value": "http://om4mfzope.bkt.clouddn.com/2017-03-27-10-55-18115"
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
                  "id": 5,
                  "content": "好",
                  "comment_time": "2017-04-10 15:49:49",
                  "at_account_id": null,
                  "comment_id_p": null,
                  "comment_id": null,
                  "username": "Encore日娱酱",
                  "avatar": "http://onz6odc5j.bkt.clouddn.com/2017-05-11-13-47-47518?imageView2/2/w/100",
                  "account_id": 488,
                  "comment_comment": []
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



