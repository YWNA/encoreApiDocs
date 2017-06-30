* 接口地址：/unpraise

* 提交方式：POST

* 接口参数：

  * id：多个动态编号（帖子）（数组的json字符串）

* 接口返回：

  ```json
  {
      "code": 1,
      "data": true
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



