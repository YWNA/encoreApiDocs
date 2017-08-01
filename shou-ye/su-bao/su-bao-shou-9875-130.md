* 本接口用于
  * 速报首页
  * 速报首页中各个类别中的《更多》
  * 上述两种情景下返回的数据格式一样
* 接口地址：/news

* 版本号：1.3.0

* 提交方式：POST

* 接口参数：

  * category\_id：非必填；1为速报资讯，2为资源，3为event，4为Encore号

  * page：非必填；页码（第一页的页码为1）

* 接口返回：

  ```json
  {
      "code": 1,
      "data": [
          {
              "news_id": 24973,
              "account_id": 169,
              "read_num": 3007,
              "title": "菅田将晖新曲封面写真公开，表情注目",
              "create_time": "1天前",
              "label_id": 1,
              "account_data": {
                  "uid": 169,
                  "username": "菅田将晖",
                  "phone": 1,
                  "country": "",
                  "pro": "",
                  "area": "",
                  "sex": 2,
                  "address": "",
                  "register_time": "2017-03-24 07:16:43",
                  "avatar": "http://om4mfzope.bkt.clouddn.com/2017-03-27-16-12-00749?imageView2/2/w/100",
                  "sinature": "",
                  "is_member": 0,
                  "is_manager": 0
              },
              "image": [
                  "http://cdnsocial.jiumaojia.com/default_avatar.jpg?imageView2/2/w/600"
              ],
              "type": "image"
          }
      ]
  }
  ```



