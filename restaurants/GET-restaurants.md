# GET restaurants

음식점 검색 시 음식점들의 목록을 반환

## URI

- restaurants


## Header Parameters


## Optional Parameters

- input : restaurant name
- address : 음식점 주소. 지도 사용시 적용.

## Required Parameters

## Request URL Snippet

- /restaurants?input={검색어}


## Simple Response

```{.json}
{
  "restaurants": [
    {
      "marker": {
        "LatLng" : {
          "latitude": 35.22977,
          "longitude": 126.845971
        }
      },
      "address": "Gwangju",
      "id": 1023,
      "order": 1,
      "name": "Star Wars",
      "branch_name": "Chumdan",
      "status": {
        "possible_review_type": "000",
        "registered_reivew_type": "000"
      }
    },
  ]
}
```

* 001 순서대로 음식점, 술집, 카페 참 거짓을 나타냄

