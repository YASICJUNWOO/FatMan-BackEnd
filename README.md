# BackEnd
<h1 align="middle">출동, 팻맨! - 조깅을 즐겁게</h1>

<p align="middle"></p>

## 🌳 소개

# 🏃조깅의 목적지(목표치) 설정 #
- 지도에 랜덤한 목적지가 생성됩니다.
  - 이는 지도에 마크로 표시되며 특정 시간이 지나면 지도에서 사라지게 됩니다.

- AR로 구현된 몬스터잡기
  - 우리의 목적지는 몬스터가 출현하는 곳입니다. 목적지에 도착해서 AR을 통해 구현된 몬스터를 잡아봐요.

- 랭킹 비교
  - 금주의 MVP는 누구일까?? 지역 내 같은 앱을 사용하는 유저끼리 누가 가장 많은 몬스터를 잡았나 비교해봐요.
       

## ⚒ 프로젝트 기술 스택
- Java 17
- Spring Boot 3.1.4
- Spring Data JPA
- Spring Security
- AWS EC2, BeansTalk, S3, RDS, GitHub Action
- MySQL


## 🎯 ERD
<img width="1009" alt="image" src="https://github.com/YASICJUNWOO/FatMan-BackEnd/assets/99794552/f27c48e3-0c8d-4426-b4dd-7498e4235352">


## 🎯 시스템 아키텍처
<img width="472" alt="image" src="https://github.com/YASICJUNWOO/FatMan-BackEnd/assets/99794552/2c21d96b-3495-4e4c-aaf6-d262d86ad8ce">



## 개발 내용
### 구현 화면
<img width="247" alt="image" src="https://github.com/YASICJUNWOO/FatMan-BackEnd/assets/99794552/82779cd0-fc2f-434b-9eed-2ebb9a867b77"> ||
<img width="247" alt="image" src="https://github.com/YASICJUNWOO/FatMan-BackEnd/assets/99794552/8b79c2ab-e703-4d42-8bd3-7756d537f36e"> || <img width="244" alt="image" src="https://github.com/YASICJUNWOO/FatMan-BackEnd/assets/99794552/7d315bea-da35-49d6-85b0-144890b61735">

<img width="247" alt="image" src="https://github.com/YASICJUNWOO/FatMan-BackEnd/assets/99794552/87bbccf6-d5c0-4f99-b8ec-feda07343bab"> || <img width="249" alt="image" src="https://github.com/YASICJUNWOO/FatMan-BackEnd/assets/99794552/680c64bd-1dcc-46f0-8ec9-3f0d26085015">
|| <img width="249" alt="image" src="https://github.com/YASICJUNWOO/FatMan-BackEnd/assets/99794552/149b3120-8da0-4475-b640-732c214f476d">

 || <img width="261" alt="image" src="https://github.com/YASICJUNWOO/FatMan-BackEnd/assets/99794552/cb309f8f-dfde-4e20-9654-7e988fb27390">
 || <img width="260" alt="image" src="https://github.com/YASICJUNWOO/FatMan-BackEnd/assets/99794552/5de423e1-af55-4445-b3c0-bb23bbc10738">
 || <img width="246" alt="image" src="https://github.com/YASICJUNWOO/FatMan-BackEnd/assets/99794552/c516c0d3-8ef3-4a23-b045-aff2fce96bca">
 ---

## 👨‍💻 협업 규칙
### 1. 브랜치 규칙
feature/{기능} 형식

예시 : feature/Login, feature/Chart

### comment


### 2. Commit Message
* feat : 새로운 기능 추가
* fix : 버그 수정, 기능 수정
* docs : 문서 수정
* refactor : 코드 리팩토링 (변수명 수정 등)
* test : 테스트 코드, 리팩토링 테스트 코드 추가
* style : 코드 스타일 변경, 코드 자체 변경이 없는 경우
* remove : 파일 또는 코드, 리소스 제거
* resource : 이미지 리소스, prefab 등의 코드와 상관없는 리소스 추가

예시 :
* resource : 이미지 리소스, prefab 등의 코드와 상관없는 리소스 추가
* feat : Add translation to missing strings
* feat : Disable publishing
* feat : Sort list context menu
* feat : Resize minimize/delete handle icons so they take up the entire topbar
* fix : Fix typo in cleanup.sh file
