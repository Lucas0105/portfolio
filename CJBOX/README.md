# 프로젝트 주제
영화 추천 알고리즘 기반 커뮤니티 서비스

# 프로젝트 링크
https://github.com/Lucas0105/CJBOX

# 제작 기간 & 참여 인원
2022년 10월 ~ 11월

# 사용한 기술 (기술 스택)
Django(Serializer, DRF), Vue

# 역할
BackEnd

# ERD

# 핵심 기능 
- 리뷰 감성 분석을 통해 사용자의 리뷰가 긍정적인지 부정적인지 판별할 수 있습니다.
- 소셜 로그인이 가능합니다.(카카오, 구글, 네이버)
- 영화 추천 알고리즘
    - 사용자가 마이리스트에 추가한 영화의 장르를 count 합니다.

    - 마이리스트에 추가한 영화 장르 중 가장 많은 수의 장르를 3개 선택합니다.

    - 3개의 장르 중 랜덤으로 해당하는 영화 15개를 보여줍니다.

    - 이때 랜덤의 기준이 인기도가 높은 순, 개봉일이 빠른 순, 평점이 높은 순, 무작위 랜덤이 될 수 있습니다.
    - 사용자에대한 정보가 없을 시 평점, 인기도, 개봉일 기준으로 내림차순하여 15개의 영화를 랜덤으로 추천해줍니다.

# 회의
- README 파일을 통해 이슈를 관리 했습니다.
- 매일 5시 30분에 작업한 내용에 대해 공유하고 이슈를 남겼습니다.

# 회고 / 느낀 점
프론트앤드에서 데이터 Response에 대해 많은 변경이 생겼던 프로젝트였습니다.

<br>

2주라는 짧은 시간에 2명이서 프로젝트를 진행하다보니 설계도 부족하고 기능에 대한 이해도 부족하였습니다.
그러다보니 data의 변경이 자주 발생하게 되었습니다.     

계속 변경되는 데이터를 전송하기 위해 데이터의 형식이 변경되는 경우가 많이 발생하였습니다.     
만약 데이터라는 큰 객체를 만들고 해당 객체에 데이터를 추가하거나 변경하는 형식으로 진행하였다면 변경되는 데이터에 대한 유지보수에 좋았을 것이라는 생각을 하였습니다.

<br>

짧은 시간의 프로젝트 기간때문에 압박감을 느끼는 프로젝트였지만 계속해서 이슈를 공유하며 개발을 진행하다보니 낭비되는 시간 없이 알차게 진행한 프로젝트였습니다.