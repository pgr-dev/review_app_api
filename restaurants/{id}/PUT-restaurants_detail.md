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
  "id": 1,
  "name": "소보쿠",
  "branch_name": "첨단점",
  "address": "광주 광산구",
  "floor": 1,
  "possible_review_type": "100",
  "pic": "url",
}
```

* 100 형식 : 음식점, 술집, 카페 순으로 참 거짓을 나타냄



