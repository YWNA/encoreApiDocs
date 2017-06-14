* 接口地址：/news

* 提交方式：POST

* 接口参数：

  * category\_id：速报类别编号（速报类别接口返回数据中的id）

  * page：页码（第一页的页码为1）

* 接口返回：

  ```json
  {
      "code": 1,
      "data": [
          {
              "id": 20187,
              "Id": 20187,
              "section_id": 488,
              "title": "丝般柔顺丨九头身的菜菜绪配上丝般柔顺的黑发又是一阵狂拽酷呢！",
              "content": "菜菜緒出演 P&amp;G 潘婷 TV CM 【もう戻れない 菜々緒さん篇】",
              "category_id": 0,//速报来源编号
              "create_time": 1496713815000,//创建时间
              "category_category_id": 1,//速报类别编号
              "video_path": "http://video.jiumaojia.com/001NFMBcjx07bEsFJy6Q010f11003u100k01.mp4",
              "read_num": 1834,//阅读数量
              "source_image":"http://om4mfzope.bkt.clouddn.com/2017-06-06-09-40-44415?imageView2/2/w/600",//速报来源图片
              "source_id":1,//速报来源编号
              "image": [ //速报相关图片
                  "http://om4mfzope.bkt.clouddn.com/2017-06-06-09-40-44415?imageView2/2/w/600"
              ],
              "account_data": { //速报发布者用户信息
                  "uid": 488,
                  "username": "Encore日娱酱",
                  "phone": 1,
                  "sex": 1,
                  "address": "",
                  "register_time": "2017-04-10 15:26:08",
                  "avatar": "http://onz6odc5j.bkt.clouddn.com/2017-05-11-13-47-47518?imageView2/2/w/100",
                  "sinature": ""
              },
              "type": "video", //速报类别
              "comments_num": 0, //评论数量
              "praise_num": 0, //点赞数量
              "if_praise": 0 //当前用户是否对该条速报点赞
          },
          {
              "id": 20187,
              "section_id": 488,
              "title": "丝般柔顺丨九头身的菜菜绪配上丝般柔顺的黑发又是一阵狂拽酷呢！",
              "content": "菜菜緒出演 P&amp;G 潘婷 TV CM 【もう戻れない 菜々緒さん篇】",
              "category_id": 0,
              "create_time": 1496713815000,
              "category_category_id": 1,
              "video_path": "http://video.jiumaojia.com/001NFMBcjx07bEsFJy6Q010f11003u100k01.mp4",
              "read_num": 1834,
              "Id": 20187,
              "image": [
                  "http://om4mfzope.bkt.clouddn.com/2017-06-06-09-40-44415?imageView2/2/w/600"
              ],
              "account_data": {
                  "uid": 488,
                  "username": "Encore日娱酱",
                  "phone": 1,
                  "sex": 1,
                  "address": "",
                  "register_time": "2017-04-10 15:26:08",
                  "avatar": "http://onz6odc5j.bkt.clouddn.com/2017-05-11-13-47-47518?imageView2/2/w/100",
                  "sinature": ""
              },
              "type": "video",
              "comments_num": 0,
              "praise_num": 0,
              "if_praise": 0
          }
      ]
  }
  ```



