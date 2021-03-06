# getTutorList


#### Description
在教师列表查询页获取教师列表
#### Resquet Method
GET
#### Request Parameters

| Name | Type | Mandatory | Default | Description |
| -- | -- | -- | -- | -- |
|  | String | YES | -- |  |



#### Response
| Name | Type | Mandatory | Default | Description |
| -- | -- | -- | -- | -- |
| Response | JSON | YES| | 教师列表  |

#### Response 参数
| Name |  Description | Type | Mandatory | Default |
| -- | -- | -- | -- | -- |
| tutor_id | 教员ID | | |   |
| name | 教员姓名，有可能是真名或者nickname | | |   |
| head_photo | 教员头像地址| | |   |
| signiture | 教员个人签名 | | |   |
| gender_eng | 教员性别 | | |   |
| career | 教员职业 | | |   |
| edu_level | 只显示教员最高学历 | | |   |
| university | 只显示教员最高学历的大学 | | |   |
| total_class_time | 教员在本平台的总授课时长 | | |   |
| rating | 教员评分 | | |   |
| price | 教员课时价格 | | |   |
| distance | 学员和教员的距离，需要传入的学生位置参数确定 | | |   |

#### Request Example

|Request URL | "http://112.74.81.48/zhihuieducation/apitutorinfocontroller/getTutorList" |
| --| -- |


#### Response Example

```
[
    {
        "tutor_id": "1",
        "name": "陈大文",
        "head_photo": "http://112.74.81.48/zhihuieducation/webApp/app/res/tutor_photo/6.jpg",
        "signiture": "没有教不会的学生",
        "gender_eng": "male",
        "career": "兼职教师",
        "edu_level": "研究生",
        "university": "江西大学",
        "total_class_time": "10",
        "rating": "5",
        "price": "0",
        "distance": ""
    },
    {
        "tutor_id": "2",
        "name": "李文文",
        "head_photo": "http://112.74.81.48/zhihuieducation/webApp/app/res/tutor_photo/4.jpg",
        "signiture": "相信自己一定可以",
        "gender_eng": "female",
        "career": "在职教师",
        "edu_level": "本科",
        "university": "广东工业大学",
        "total_class_time": "19",
        "rating": "4.5",
        "price": "100",
        "distance": ""
    },
    {
        "tutor_id": "11",
        "name": "赵同学",
        "head_photo": "http://112.74.81.48/zhihuieducation/webApp/app/res/tutor_photo/1.jpg",
        "signiture": "我是数学大牛",
        "gender_eng": "male",
        "career": "大学生",
        "edu_level": "本科",
        "university": "吉林大学",
        "total_class_time": "15",
        "rating": "4.8",
        "price": "200",
        "distance": ""
    },
    {
        "tutor_id": "13",
        "name": "刘同学",
        "head_photo": "http://112.74.81.48/zhihuieducation/webApp/app/res/tutor_photo/2.jpg",
        "signiture": "祝您圆梦",
        "gender_eng": "male",
        "career": "在职教师",
        "edu_level": "研究生",
        "university": "香港大学",
        "total_class_time": "43",
        "rating": "4.3",
        "price": "200",
        "distance": ""
    },
    {
        "tutor_id": "14",
        "name": "任同学",
        "head_photo": "http://112.74.81.48/zhihuieducation/webApp/app/res/tutor_photo/3.jpg",
        "signiture": "没有教不会的学生",
        "gender_eng": "male",
        "career": "兼职教师",
        "edu_level": "博士",
        "university": "香港理工大学",
        "total_class_time": "8",
        "rating": "5",
        "price": "150",
        "distance": ""
    }
]
```






