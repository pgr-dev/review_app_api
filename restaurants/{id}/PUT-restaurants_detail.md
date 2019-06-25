# PUT restaurants detail

특정 음식점의 정보를 수정

## URI

- restauratns/{pk}


## Header Parameters


## Optional Parameters


## Required Parameters



## Simple Request Body

```{.json}
{
    "id": 6892,
    "rstrtdetailinfo": {
        "id": 4,
        "size": "S",
        "is_duplex": false,
        "is_room": false,
        "is_self_service": false,
        "is_bar_table": null,
        "is_restroom": true,
        "restroom_cleanliness": ""
    },
    "name": "소보쿠",
    "branch_name": "동명점",
    "address": "광주광역시 동구 동명동 135-18",
    "floor": 3,
    "possible_review_type": "110",
    "status": "p_Approved",
    "register_time": null,
    "info_register_time": null,
    "is_active": true,
    "registered_review_type": "",
    "active": null,
    "reviewer": null
}
```

* 100 형식 : 음식점, 술집, 카페 순으로 참 거짓을 나타냄



