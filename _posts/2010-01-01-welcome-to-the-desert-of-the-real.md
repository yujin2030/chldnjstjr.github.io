---
date: 2020-10-01T04:00:05.000Z
layout: post
title: 주사위의 기대값은 진짜 3.5인가?
subtitle: 주사위 1000번 굴리면 진짜 평균이 3.5가 나오는지 한 번 알아보자
description: >-
  Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
  tempor incididunt ut labore et dolore magna aliqua.
image: >-
  https://cdn.pixabay.com/photo/2016/07/07/16/46/roll-the-dice-1502706_960_720.jpg
optimized_image: >-
  https://cdn.pixabay.com/photo/2016/07/07/16/46/roll-the-dice-1502706_960_720.jpg
category: Probability Experiment
tags:
  - Probability
  - Experiment
  - Probability Experiment
  - 확률
  - 주사위 
  - 평균 
  - 기대값
author: 최원석
paginate: true
---
주사위 하나를 던졌을 때 나오는 눈의 기대값이 3.5라는 것은 통계학개론, 기초확률론 강의에서 수도 없이 들었다. 근데 정말로, 진짜로 그것이 맞는지 내 두 눈으로 확인하지 않고서야 그냥 넘어가지 못하는 바보같은 성격 때문에 주사위 1000번(정확히는 1000개의 눈)을 던져 평균을 구해보았다. 그리고 믿을 수 없게도 결과는.

> 본 글은 통계학이 어려운 통계학과 학부 졸업생이 작성한 글로 

우선 아래와 같이 실험을 간단히 정리했다. 

#### 질문
주사위의 기대값은 정말로 3.5인가? 아니, 정말 3.5에 가깝기라도 한 것일까? 

#### 목적
위 질문에 대한 답을 구하고자 주사위를 무수히 많이 던져 나온 1000개의 눈들의 합의 평균을 구한다. 

#### 실험 방법
주사위 10개를 100번 던진다. 
1r(주사위 10개x10번)마다 나온 주사위의 눈을 엑셀에 기록한다.

#### 실험 도구
* 주사위 
ABM 파티 칼라 정육면체 주사위 10EA
주사위 크기: 1.4cm X 1.4cm X 1.4cm
주사위 무게: 19g
제조사: 도매콜
원산지: 중국 

* 기초확률론 제 3판, 신양우 지음 (경문사)
주사위를 던질 때 받침대로 활용하였다.
(교재 비하 의도는 전혀 없으며 단지 본 교재로 공부하던 중 호기심에 바로 책을 뒤집어 본의 아니게 책을 받침대로 사용하게 되었습니다. 죄송합니다.)

#### 실험 일자 및 장소
* 2020년 10월 1일 2:30 ~ 3:30 
* 한양대학교 서울캠퍼스 제 2학생생활관 1층 식당

#### 실험 특이사항 
주사위를 굴리는 데 너무 시끄러웠던 나머지 옆 자리의 유학생이 굉장히 눈치를 많이 주었다. 

--실험 결과--

## Code

Cum sociis natoque penatibus et magnis dis `code element` montes, nascetur ridiculus mus.

```js
// Example can be run directly in your JavaScript console

// Create a function that takes two arguments and returns the sum of those arguments
var adder = new Function("a", "b", "return a + b");

// Call the function
adder(2, 6);
// > 8
```

Aenean lacinia bibendum nulla sed consectetur. Etiam porta sem malesuada magna mollis euismod. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa.

## Lists

Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Aenean lacinia bibendum nulla sed consectetur. Etiam porta sem malesuada magna mollis euismod. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa justo sit amet risus.

* Praesent commodo cursus magna, vel scelerisque nisl consectetur et.
* Donec id elit non mi porta gravida at eget metus.
* Nulla vitae elit libero, a pharetra augue.

Donec ullamcorper nulla non metus auctor fringilla. Nulla vitae elit libero, a pharetra augue.

1. Vestibulum id ligula porta felis euismod semper.
2. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.
3. Maecenas sed diam eget risus varius blandit sit amet non magna.

Cras mattis consectetur purus sit amet fermentum. Sed posuere consectetur est at lobortis.

Integer posuere erat a ante venenatis dapibus posuere velit aliquet. Morbi leo risus, porta ac consectetur ac, vestibulum at eros. Nullam quis risus eget urna mollis ornare vel eu leo.

## Images

Quisque consequat sapien eget quam rhoncus, sit amet laoreet diam tempus. Aliquam aliquam metus erat, a pulvinar turpis suscipit at.

![placeholder](https://placehold.it/800x400 "Large example image") ![placeholder](https://placehold.it/400x200 "Medium example image") ![placeholder](https://placehold.it/200x200 "Small example image")

## Tables

Aenean lacinia bibendum nulla sed consectetur. Lorem ipsum dolor sit amet, consectetur adipiscing elit.

<table>
  <thead>
    <tr>
      <th>Name</th>
      <th>Upvotes</th>
      <th>Downvotes</th>
    </tr>
  </thead>
  <tfoot>
    <tr>
      <td>Totals</td>
      <td>21</td>
      <td>23</td>
    </tr>
  </tfoot>
  <tbody>
    <tr>
      <td>Alice</td>
      <td>10</td>
      <td>11</td>
    </tr>
    <tr>
      <td>Bob</td>
      <td>4</td>
      <td>3</td>
    </tr>
    <tr>
      <td>Charlie</td>
      <td>7</td>
      <td>9</td>
    </tr>
  </tbody>
</table>

Nullam id dolor id nibh ultricies vehicula ut id elit. Sed posuere consectetur est at lobortis. Nullam quis risus eget urna mollis ornare vel eu leo.
