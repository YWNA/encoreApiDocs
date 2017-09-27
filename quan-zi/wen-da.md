* 接口地址：/post/detail

* 提交方式：POST

* 接口参数：

  * post\_id：帖子编号

  * page：页码（第一页的页码为1）

* 接口返回：

  ```json
  {
      "code": 1,
      "data": {
          "post_id": 10608,
          "title": "哈哈哈",
          "content": [
              {
                  "image": "http://cdnsocial.jiumaojia.com/1506050858313158282",
                  "type": "image",
                  "value": "http://cdnsocial.jiumaojia.com/1506050858313158282",
                  "image_info": {
                      "size": 1671393,
                      "format": "jpeg",
                      "width": 1080,
                      "height": 1920,
                      "colorModel": "ycbcr"
                  }
              },
              {
                  "content": "嘻嘻",
                  "type": "text",
                  "value": "嘻嘻"
              },
              {
                  "content": " ",
                  "type": "text",
                  "value": " "
              }
          ],
          "content2": "a:3:{i:0;a:1:{s:5:\"image\";s:50:\"http://cdnsocial.jiumaojia.com/1506050858313158282\";}i:1;a:1:{s:7:\"content\";s:6:\"嘻嘻\";}i:2;a:1:{s:7:\"content\";s:1:\" \";}}",
          "read_num": 3,
          "account_id": 158282,
          "account_avatar": "http://cdnsocial.jiumaojia.com/1505727033566158282",
          "account_name": "屎壳郎💩",
          "account_label": 0,
          "create_time": "5天前",
          "comments_num": 0,
          "praise_num": 0,
          "if_praise": 0,
          "is_save": 0,
          "image": [
              "http://cdnsocial.jiumaojia.com/default_avatar.jpg"
          ],
          "image_num": 0,
          "banner_image": "http://cdnsocial.jiumaojia.com/default_avatar.jpg",
          "role_data": [],
          "share_content": "哈哈哈",
          "content_text": "嘻嘻 ",
          "comments": [],
          "praise_account": [],
          "section_data": [],
          "api_description": {
              "sort_by": "该字段值为1代表楼主排序，2代表楼层排序，3代表点赞数量排序；"
          }
      }
  }
  ```



