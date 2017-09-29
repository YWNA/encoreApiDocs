* 接口场景

  * 获取速报资讯的所有点赞信息，则news\__id必填，page和page\_size默认1和8_

  * 获取动态帖子的所有点赞信息，则post\__id必填，page和page_\_size默认1和8

  * 对帖子点赞，type必填为post，value则为速报编号

  * 对速报点赞，type必填为news，value则为帖子编号

* 接口地址：/praise

* 提交方式：POST

* 接口参数：

  * page：页码
  * page\_size：页数
  * news\_id：速报资讯编号
  * post\_id：动态帖子编号
  * type：
  * value：

* 接口返回：

  ```json
  {
      "code": 1,
      "data": [
          {
              "account_id": 25065,
              "account_username": "董晓菁cris",
              "account_avatar": "http://wx.qlogo.cn/mmopen/ajNVdqHZLLDqSsSYLODdzrK6jDWfiaU3t2wUkiceIrk7Tvia1w0hQibx8VvE542eL7LkibWaKJdicak71DKzp3ia2TPPg/?imageView2/2/w/100",
              "praise_time": "2017-06-29 17:35:48",
              "post_id": 1,
              "post_content": "我是第一个诶",
              "post_image": "http://cdndevelop.jiumaojia.com/2017-05-17-20-26-32115"
          },
          {
              "account_id": 25065,
              "account_username": "董晓菁cris",
              "account_avatar": "http://wx.qlogo.cn/mmopen/ajNVdqHZLLDqSsSYLODdzrK6jDWfiaU3t2wUkiceIrk7Tvia1w0hQibx8VvE542eL7LkibWaKJdicak71DKzp3ia2TPPg/?imageView2/2/w/100",
              "praise_time": "2017-06-29 17:35:48",
              "post_id": 1,
              "post_content": "我是第一个诶",
              "post_image": "http://cdndevelop.jiumaojia.com/2017-05-17-20-29-12787"
          },
          {
              "account_id": 26026,
              "account_username": "秦小么",
              "account_avatar": "http://wx.qlogo.cn/mmopen/iakbnHP0m3I9IoUrJF5gAricUicKicsbAvfttT0eibzRKAbkpyRm8kZNfc7SFrTvt03555JjiabJWPpHyKWVzalpJm4a0wHH03mMxa/?imageView2/2/w/100",
              "praise_time": "2017-06-29 17:35:48",
              "post_id": 1,
              "post_content": "我是第一个诶",
              "post_image": "http://cdndevelop.jiumaojia.com/2017-05-17-20-26-32115"
          },
          {
              "account_id": 26026,
              "account_username": "秦小么",
              "account_avatar": "http://wx.qlogo.cn/mmopen/alpJm4a0wHH03mMxa/?imageView2/2/w/100",
              "praise_time": "2017-06-29 17:35:48",
              "post_id": 1,
              "post_content": "我是第一个诶",
              "post_image": "http://cdndevelop.jiumaojia.com/2017-05-17-20-29-12787"
          },
          {
              "account_id": 25328,
              "account_username": "张xx(´-ω-`)",
              "account_avatar": "http://wx.qlogo.cn/mmopen/7d3GiaZjobrH2dLnBHVA5eYw91XFoyfrFQAfuHD5Xrouic0bReuwTnb41W2uOKWRgYBrHtZMrPzzQibyVrEhS1PMWicQSicAMEhR0/?imageView2/2/w/100",
              "praise_time": "2017-06-29 17:35:48",
              "post_id": 1,
              "post_content": "我是第一个诶",
              "post_image": "http://cdndevelop.jiumaojia.com/2017-05-17-20-26-32115"
          },
          {
              "account_id": 25328,
              "account_username": "张xx(´-ω-`)",
              "account_avatar": "http://wx.qlogo.cn/mmopen/7d3GiaZjobrH2dLnBHVA5eYw91XFoyfrFQAfuHD5Xrouic0bReuwTnb41W2uOKWRgYBrHtZMrPzzQibyVrEhS1PMWicQSicAMEhR0/?imageView2/2/w/100",
              "praise_time": "2017-06-29 17:35:48",
              "post_id": 1,
              "post_content": "我是第一个诶",
              "post_image": "http://cdndevelop.jiumaojia.com/2017-05-17-20-29-12787"
          },
          {
              "account_id": 25193,
              "account_username": "麦粒肿",
              "account_avatar": "http://wx.qlogo.cn/mmopen/01lkjzpPHicicK7nFHUFiaQPTIIVd2bQTBkDko0tXWG0dZTkr9AwmB87iawryPMZBEFNA4RVo2ibzMSKQliakUkl16ILAEGRKU15nf/?imageView2/2/w/100",
              "praise_time": "2017-06-29 17:35:48",
              "post_id": 1,
              "post_content": "我是第一个诶",
              "post_image": "http://cdndevelop.jiumaojia.com/2017-05-17-20-26-32115"
          },
          {
              "account_id": 25193,
              "account_username": "麦粒肿",
              "account_avatar": "http://wx.qlogo.cn/mmopen/01lkjzpPHicicK7nFHUFiaQPTIIVd2bQTBkDko0tXWG0dZTkr9AwmB87iawryPMZBEFNA4RVo2ibzMSKQliakUkl16ILAEGRKU15nf/?imageView2/2/w/100",
              "praise_time": "2017-06-29 17:35:48",
              "post_id": 1,
              "post_content": "我是第一个诶",
              "post_image": "http://cdndevelop.jiumaojia.com/2017-05-17-20-29-12787"
          }
      ]
  }
  ```



