# POST review

Save the review of specific restaurant


## Header Parameters


## Optional Parameters


## Required Parameters

  - id : restaurant id
  - size : 소("S"), 중("M"), 대("L"), 특대("G")
  - is_duplex : 참(1), 거짓(0)
  - is_room : 참(1), 거짓(0)
  - is_self_service : 참(1), 거짓(0)
  - is_restroom : 참(1), 거짓(0)
  - restroom_cleanliness : 상("High"), 중("Mid"), 하("Low")


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