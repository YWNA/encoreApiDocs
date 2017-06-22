* 接口地址：/news/praise

* 提交方式：POST

* 接口参数：

  * news\_id：速报编号

* 接口返回：

  ```json
  {
      "code": 1,
      "data": {
          "account_username": "Encore日娱酱",
          "account_id": "488",
          "account_avatar": "http://onz6odc5j.bkt.clouddn.com/2017-05-11-13-47-47518?imageView2/2/w/100",
          "message": "点赞成功"
      }
  }
  ```

* 取消点赞同为该接口，返回数据格式如下：

```json
{
    "code": 1,
    "data": {
        "account_username": "Encore日娱酱",
        "account_id": "488",
        "account_avatar": "http://onz6odc5j.bkt.clouddn.com/2017-05-11-13-47-47518?imageView2/2/w/100",
        "message": "取消点赞成功"
    }
}
```



