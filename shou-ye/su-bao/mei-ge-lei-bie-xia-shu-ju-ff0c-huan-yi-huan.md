* 接口地址：/news

* 提交方式：POST

* 接口参数：

  * 速报，资源，剧评，演出，字幕组。news\_rand\_by必填，且值相应分别为1，2，3，4，9

  * 问答。post\_rand\_by必填，且值相应分别为6

* 返回数据

  * ```json
    {
        "code": 1,
        "data": [
            {
                "news_id": 26992,
                "account_id": 33546,
                "category_id": null,
                "video_path": "http://video.jiumaojia.com/001r3Au1jx07by3eUoJW010f11004nXo0k01.mp4",
                "video_image": "http://cdnsocial.jiumaojia.com/2017-09-01-14-21-05587",
                "read_num": 7793,
                "title": "太贺和臼田麻美主演漫改电影「南瓜与美乃滋」预告片公开",
                "create_time": "23天前",
                "classType": 0,
                "class_type": 0,
                "is_tv": 0,
                "image": [
                    "http://cdnsocial.jiumaojia.com/2017-09-01-14-19-05796?imageView2/2/w/600"
                ],
                "banner_image": "http://cdnsocial.jiumaojia.com/2017-09-01-14-19-05796?imageView2/2/w/600",
                "account_data": {
                    "uid": 33546,
                    "username": "mikiiii酱",
                    "phone": "19900001694",
                    "country": "",
                    "pro": "",
                    "area": "",
                    "sex": 2,
                    "address": "",
                    "register_time": "2017-07-13 16:20:18",
                    "avatar": "http://cdnsocial.jiumaojia.com/2017-07-13-16-20-18593?imageView2/2/w/100",
                    "sinature": "",
                    "is_member": 1,
                    "label": 0,
                    "source_avatar": "http://cdnsocial.jiumaojia.com/2017-07-13-16-20-18593",
                    "is_manager": 0
                },
                "type": "video",
                "comments_num": 1,
                "praise_num": 0,
                "is_store": 0,
                "role_data": [
                    {
                        "role_type": 3,
                        "role_name": "UPer",
                        "role_description": "UPer",
                        "api_description": "role_type=1代表圈主,2代表机构,3代表自媒体,4代表明星;本接口若提供section_page字段,则仅返回关注的圈子数据（每页8条）"
                    }
                ],
                "if_praise": 0
            }
        ]
    }
    ```

    ```

    ```



