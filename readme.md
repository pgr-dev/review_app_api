# pg-api


- GET [restaurants]()
- GET [restaurants detail]()
- POST [review]()


## restaurant

제목은 다음과 같은 형식으로 이루어져 있습니다.
`주고받는위치(위치A_접속사_위치B)-목적
 - 접속사가 *"to"*일시 위치A에서 위치B로 일방적으로 보내는 정보입니다.
 - 접속사가 *"with"*일시 위치A와 위치B가 서로 통신하고 주고 받는 정보입니다.

 *모든 api는 요청(request)와 답장(response)로 이루어져 있습니다!!*
`



>- server_to_mainSearch-restaurantsInfo(음식점 검색 시 서버에서 메인검색페이지에서 받는 정보)
>>- server_with_storePage-storeInfo(서버와 음식점 정보 작성 페이지 사이에서 서로 주고받는 정보)
>>- 
