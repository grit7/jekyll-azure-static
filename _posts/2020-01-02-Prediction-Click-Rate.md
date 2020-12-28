---
title: "클릭률 예측"
date: 2020-01-02 16:00:00 +0400
categories: 공모전
defaults:
  # _posts
  - scope:
      path: ""
      type: posts
    values:
      layout: single
      author_profile: true
      read_time: true
      comments: true
      share: true
      related: true
---
#클릭률 예측
##대회 주제

* 사용자와 방문한 페이지가 주어지면 주어진 광고를 클릭할 확률 추정 모형 개발
* 온라인 광고 시장은 비식별 데이터를 사용하여 오디언스 프로파일링
* 개인화 추천을 통해 광고를 게재함
</br>
##분석 대상 : TradingWorks

* 500억 건 이상의 모바일 데이터, 3천 개 이상의 매체, Unique User 4천만명 규

##TradingWorks 특징

* 모바일 App에 특화
* A.I 예측 마케팅은 예측된 오디언스별로 개인화된 크리에이티브를 자동 생성
* 글로벌 주요 매체에 Auto Bidding 시스템을 통해 최적의 순간, 최적의 인벤토리에 노출

###데이터

* **train.csv**
10일간의 로그 데이터들이다. 학습할 대상 인 것 같다. 550만 row를 갖는다.
</br>
* **test.csv**
학습 대상으로 부터 얻은 모델로 테스트 할 수 있는 데이터인 것 같다. 실제 10일 다음 날 하루에 대한 데이터 값이다. 이 데이터를 근거로 학습된 모델의 성능을 평가할 수 있다. 55만 row를 갖는다.
</br>
* **audience_profile.csv**
사용자의 데이터
</br>
* **submission.csv**
제출 예시 파일 데이터를 살펴보니 bid_id 컬럼 밖에 없다.
train.csv 데이터와, test.csv에도 bid_id가 있음.
bid_id가 뭘까? audience_profile을 살펴보면 bid_id가 있음.
bid는 입찰이라는 뜻인데... 아~ 광고를 클릭했는지 안했는 지 0과 1로 표시하는거구나.

    </br>
    일단 train.csv과 audience_profile.csv 가지고 학습을 해야 함. 어디서부터 시작해야할까?>>>>>>>
