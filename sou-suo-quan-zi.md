* 接口地址：/section/search

* 提交方式：POST

* 接口参数：

  * word：内容

* 接口返回：

  ```json
  {
      "code": 1,
      "data": [
          {
              "section_id": 18,
              "section_name": "AKB48",
              "section_avatar": "http://om4mfzope.bkt.clouddn.com/2017-03-27-10-33-36759?imageView2/2/w/100",
              "is_follow": 0
          },
          {
              "section_id": 19,
              "section_name": "SKE48 ",
              "section_avatar": "http://om4mfzope.bkt.clouddn.com/2017-03-27-10-35-39315?imageView2/2/w/100",
              "is_follow": 0
          },
          {
              "section_id": 20,
              "section_name": "NMB48",
              "section_avatar": "http://om4mfzope.bkt.clouddn.com/2017-03-27-10-37-39603?imageView2/2/w/100",
              "is_follow": 0
          },
          {
              "section_id": 21,
              "section_name": "HKT48",
              "section_avatar": "http://om4mfzope.bkt.clouddn.com/2017-03-27-10-39-07681?imageView2/2/w/100",
              "is_follow": 0
          },
          {
              "section_id": 587,
              "section_name": "STU48",
              "section_avatar": "http://om4mfzope.bkt.clouddn.com/2017-06-01-11-22-43262?imageView2/2/w/100",
              "is_follow": 0
          },
          {
              "section_id": 588,
              "section_name": "NGT48",
              "section_avatar": "http://om4mfzope.bkt.clouddn.com/2017-06-01-11-25-10207?imageView2/2/w/100",
              "is_follow": 0
          }
      ]
  }
  ```

* ### **圈子搜索时的热门圈子**
* 接口地址：/section/hot

* 接口返回：

```json
{
    "code": 1,
    "data": [
        {
            "section_id": 253,
            "num": 3274,
            "section_name": "日剧",
            "section_avatar": "http://onz6odc5j.bkt.clouddn.com/2017-05-02-15-09-22297?imageView2/2/w/100"
        },
        {
            "section_id": 6,
            "num": 2063,
            "section_name": "嵐",
            "section_avatar": "http://om4mfzope.bkt.clouddn.com/2017-03-27-15-03-04482?imageView2/2/w/100"
        },
        {
            "section_id": 111,
            "num": 1721,
            "section_name": "新垣结衣",
            "section_avatar": "http://om4mfzope.bkt.clouddn.com/2017-03-27-15-04-19121?imageView2/2/w/100"
        },
        {
            "section_id": 180,
            "num": 1650,
            "section_name": "小栗旬",
            "section_avatar": "http://om4mfzope.bkt.clouddn.com/2017-03-27-16-46-00602?imageView2/2/w/100"
        }
    ]
}
```



