# GET reviews detail

특정 리뷰의 내용을 반환

## URI

- reviews/{pk}


## Header Parameters


## Optional Parameters


## Required Parameters


## Simple Response

```{.json}
{
  'id': 24, 
  'menu_set' : [
    {
      'id': 12,
      'type': 'GM',
      'name': '지라시덮밥',
      'description': '다양한 스시와 고기가 밥과 같이 나온다',
      'description_feedback': '더 구체적으로 적어주세요',
      'price_type': 'General',
      'price_unit': '개',
      'price': 12000,
      'star_rating': 4.5,
      'food_set': [
        {
          'id': 56,
          'name': '지라시덮밥',
          'description': '가까이서 보니 더 맛있다',
          'description_feedback': '더 구체적으로 적어주세요',
        },
        {
          'id': 57,
          'name': '서비스로 나온 초밥',
          'description': '서비스로 나온 초밥이다',
          'description_feedback': '맛도 설명해주세요',
        }
      ]
    },
  ],
  'restaurant': {
    'id': 6892,
    'rstrtdetailinfo': {
      'size': 'S',
      'is_duplex': 1, 
      'is_room': 0, 
      'is_self_service': 1, 
      'is_bar_table': 0,
      'is_restroom': 1,
      'restroom_cleanliness': 'High',
    } 
  },
  'register_time': ,
  'status': 'Modified', 
  'type': 'CAFE',
  'visit_date':,
  'rstrt_overview': '25년 경력의 일식조리사가 결까지 생각해서 뜨는 회에 소문난 매운탕과 초밥이 일품인 집',
  'rstrt_overview_feedback': '더 구체적으로 적어주세요',
  'rstrt_atmosphere': '아기자기해서 데이트 하기 좋은 분위기!',
  'rstrt_atmosphere_feedback': '잘 적었습니다',
  'comment': '나중에 또 생각나는 맛',
  'comment_feedback': '더 구체적으로 적어주세요',
  'flavor_score': 4.5, 
  'flavor_summary': '깔끔한 맛이네요',
  'flavor_summary_feedback': '더 구체적으로 적어주세요',
  'atmosphere_score': '5.0,
  'atmosphere_summary': '분위기는 매우 좋아요',
  'atmosphere_summary_feedback': '더 구체적으로 적어주세요',
  'efficiency_score': 0.5,
  'efficiency_summary': '매우 비쌉니다',
  'efficiency_summary_feedback': '더 구체적으로 적어주세요',
  'summary': '다시오고 싶지만 너무 비싼 곳',
  'summary_feedback': '더 구체적으로 적어주세요',
  'assessment': 2,
  'reviewer': '젠투펭귄',
  'pic_feedback': '더 선명하게 찍어주세요',
  'total_feedback': '전체적으로 글자 수가 너무 적습니다',
}
```

- 'id': 리뷰 고유 값
- 'menu_set': 메뉴. 리스트 안에 여러 메뉴 가능.
  - 'id': 메뉴 아이디
  - 'type': 메뉴유형 - 'GM'(일반 메뉴), 'SM'(세트 메뉴), 'CM'(코스 메뉴), 'BM'(뷔페 메뉴)
  - 'name': 메뉴이름(최대 50자)
  - 'description': 메뉴리뷰(최대 500자)
  - 'description_feedback': 메뉴리뷰 피드백(최대 500자)
  - 'price_type': 가격유형 - 'General'(일반), 'Portion'(인분), 'Size'(크기)
  - 'price_unit': 가격단위(최대 10자)
  - 'price': 가격크기
  - 'star_rating': 별점
  - 'food_set': 음식. 리스트 안에 여러 음식 가능.   
    - 'id': 음식 아이디
    - 'name': 음식 이름(최대 50자)
    - 'description': 음식 설명(최대 500자)
    - 'description_feedback': 음식 설명 피드백(최대 500자)

- 'restaurant': 음식점 관련 정보들
  - 'id': 음식점 고유 값
  - 'rstrt_detail_info': '정보'란에 있는 음식점 추가 정보들
    -  'size': 크기 - 'S'(소), 'M'(중), 'L'(대), 'G'(특대)
    -  'is_duplex': 복층 - 0(거짓), 1(참)
    -  'is_room': 룸 - 0(거짓), 1(참)
    -  'is_self_service': 셀프서비스 - 0(거짓), 1(참)
    -  'is_bar_table': 바테이블 - 0(거짓), 1(참)
    -  'is_restroom': 화장실 - 0(거짓), 1(참)
    - 'restroom_cleanliness': 화장실 청결도 - 'High'(상), 'Mid'(중), 'Low'(하)
- 'register_time': ,
- 'status': 상태 - 'Modified'(리뷰어수정), 'StandBy'(검토대기), 'Approved'(승인)
- 'type': 리뷰 타입 - 'CAFE', 'RSTRT', 'BAR'
- 'visit_date': 방문 시간
- 'rstrt_overview': 음식점 개요(최대 500자)
- 'rstrt_overview_feedback': 음식점 개요 피드백(최대 500자)
- 'rstrt_atmosphere': 분위기 설명(최대 500자)
- 'rstrt_atmosphere_feedback': 분위기 설명 피드백(최대 500자)
- 'comment': 자유로운 말(최대 500자)
- 'comment_feedback': 자유로운 말 피드백(최대 500자)
- 'flavor_score': 맛점수
- 'flavor_summary': 맛요약(최대 45자)
- 'flavor_summary_feedback': 맛요약 피드백(최대 150자)
- 'atmosphere_score': 분위기 점수
- 'atmosphere_summary': 분위기 요약(최대 45자)
- 'atmosphere_summary_feedback': 분위기 요약 피드백(최대 150자)
- 'efficiency_score': 가성비 점수
- 'efficiency_summary': 가성비 요약(최대 45자)
- 'efficiency_summary_feedback': 가성비 요약 피드백(최대 150자)
- 'summary': 한마디(최대 40자)
- 'summary_feedback': 한마디 피드백(최대 150자)
- 'assessment': 평가. 에디터의 리뷰어 평가 - 1, 2, 3
- 'reviewer': 리뷰어 이름
- 'pic_feedback': 사진 피드백(최대 150자)
- 'total_feedback': 전체 피드백(최대 500자)