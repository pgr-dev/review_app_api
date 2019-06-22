# GET users

유저의 목록을 반환

## URI

- users


## Header Parameters


## Optional Parameters


## Required Parameters



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

