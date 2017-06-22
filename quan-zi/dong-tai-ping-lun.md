* 接口地址：/post/comment

* 提交方式：POST

* 接口参数：

  * post\_id：动态编号（帖子）

  * content：评论内容

  * ~~at\_\_account\_\_id：@评论的用户编号~~

  * ~~comment\_id：评论编号~~

  * ~~comment\_\_id\_\_p：评论顶级编号~~

* 接口返回：

  ```json
  {
      "code": 1,
      "data": {
          "id": 255,
          "content": "2121",
          "comment_time": "2017-06-22 09:50:43",
          "account_id": 488,
          "post_id": 11,
          "at_account_id": 2,
          "comment_id": 476,
          "comment_id_p": 476,
          "account_username": "Encore日娱酱",
          "account_avatar": "http://onz6odc5j.bkt.clouddn.com/2017-05-11-13-47-47518?imageView2/2/w/100",
          "at_account_username": "TOKIO",
          "at_account_avatar": "http://om4mfzope.bkt.clouddn.com/2017-03-24-16-25-08127?imageView2/2/w/100",
          "is_show_at": 1
      }
  }
  ```



