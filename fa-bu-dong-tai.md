* 动态发布使用场景：  
  1. 准备发布动态时，提供已关注的圈子的数据  
  2. 发布动态信息内容

* 接口地址：/post/release

* 提交方式：POST

* 接口参数：

  * **section：1，场景1时则补充该字段，且值为1**

  * type：post帖子类型，news速报动态类型

  * category\_id：发布周边时值为5，发布问答时值为6，发布扩列时为7

  * category\_category\_id：发布周边的想入值为1，发布周边的想出为2。发布问答的提问为2。发布扩列为1

  * content：动态图文内容

  * sections：管理圈子\(圈子编号有英文逗号隔开，格式例如：1,2,3\)

* 接口返回：

* 场景1返回数据结构

* ```json
  {
      "code": 1,
      "data": [
          {
              "section_name": "NMB48",
              "section_id": 20,
              "section_avatar": "http://om4mfzope.bkt.clouddn.com/2017-03-27-10-37-39603?imageView2/2/w/100"
          },
          {
              "section_name": "山下智久",
              "section_id": 11,
              "section_avatar": "http://om4mfzope.bkt.clouddn.com/2017-03-27-10-17-18189?imageView2/2/w/100"
          }
      ]
  }
  ```
* 场景2返回数据结构

* ```json
  {
      "code": 1,
      "data": true
  }
  ```



