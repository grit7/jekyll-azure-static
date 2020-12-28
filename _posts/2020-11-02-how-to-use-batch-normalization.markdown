---
title:  "How To Use Batch Normalization"
date:   2020-11-02 18:25:42 +0900
categories: ML
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

# BatchNormalization

입력값을 정규화시킬 수 있다. 정규화시키는 이유는 많은 심층 모델 성능 향상에 효과가 있다. 1 epoch의 학습은 전체 입력 데이터를 일정한 크기의 미니 배치들로 이루어져 있을 때 BatchNormalization는 배치 크기로 나눠진 미니 배치들의 정규화를 한다.