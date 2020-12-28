---
title: "큰숫자계산기 만들기"
date: 2019-12-22 12:00:00 +0400
categories: calculator ass1 comp1000 software math descrete BigNumberCalculator
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

정수 자료형으로 표현이 불가능한 큰 정수를 어떻게 표현할 수 있을까?
그 큰 정수형의 진법 전환과 사칙연산의 방법을 알 수 있었던 프로젝트

- 코딩 스타일 카멜표기법과 파스칼표기법

  * 파스칼 표기 법은 PowerPoint 처럼 첫 문자를 대문자로 시작하고 다른 단어와 합성될 때 그 다른 단어도 첫 문자를 대문자로 시작하게 한다. 클래스 멤버 변수에 사용된다.
  * 카멜 표기법은 지역 변수 그리고 함수의 매개변수의 이름에 사용된다. ex) powerPoint
  * 클래스의 멤버 변수가 private일 경우 변수명 앞에 m을 붙이고 파스칼 표기법을 따른다.
  * 클래스의 멤버 변수가 public일 경우는 파스칼 표기법


- 클래스 내에서 언제 private, public, protected를 쓸까?

  * https://stackoverflow.com/questions/614818/in-c-what-is-the-difference-between-public-private-protected-and-having-no


- 코드를 너무 어렵게 만드는 경향이 있음.
  * 코드를 어렵게 짜면 시간이 지난 뒤 봤을 때 이해도 안감. 나중에도 봤을 때 이해가능한 코드를 작성하는게 중요함.
  * 코드를 작성하기 전에 이게 최선의 방법인지 여러 선택안들을 생각해볼 필요가 있음. 주먹구구식 코딩 금지.
