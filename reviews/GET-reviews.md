# GET review

리뷰의 목록을 반환

## URI

- reviews


## Header Parameters


## Optional Parameters

- user: 특정 유저의 리뷰 목록을 알고 싶을 때 유저 id를 입력
- restaurant: 특정 음식점의 리뷰를 알고 싶을 때 음식점 id를 입력

## Required Parameters


## Request URL Snippet

- reviews?uesr={user_id}
- reviews?restaurnat={restaurant_id}


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