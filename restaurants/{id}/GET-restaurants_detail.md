# GET restaurants detail

Return the detail of specific restaurant. 


## Header Parameters


## Optional Parameters


## Required Parameters

- id: restaurant id

## Request URL Snippet

- /restaurants/10


## Simple Response

```{.json}
{
  "id": 1,
  "name": "소보쿠",
  "branch_name": "첨단점",
  "address": "광주 광산구",
  "floor": 1,
  "possible_review_type": "100",
  "pic": "url",
  "type": "000"
}
```

* 100 형식 : 음식점, 술집, 카페 순으로 참 거짓을 나타냄