# GET restaurants

Return the list of matching restaurants. 


## Header Parameters


## Optional Parameters

- input : restaurant name
- id : restaurant id

## Required Parameters

## Request URL Snippet

- /restaurants?input={검색어}
- /restaurants?id={id}


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

