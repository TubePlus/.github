# TubePlus
현재 서비스 로그인 승인 대기중(Google Auth)
페이지 : https://my.tubeplus.online 
노션 : https://colossal-whip-d19.notion.site/ACEs-4d1370f673604fdcb7ad9a18f0442867?pvs=4
### 메인화면 

![메인화면](asset/메인화면.gif)


## 💻 업무 분장

![담당역할](asset/담당역할.png)

---

## 💻 프로젝트 소개

1. 개발 기간: 2023.09.20 ~ 2023.11.30 (총 7주)
2. 인원(총 5인)
3. 개요

- 서비스 목표: 유튜브의 커뮤니티 플러그인(최종)
- 1차 목표: 유튜브의 커뮤니티 웹페이지 생성
- [기획배경](asset/기획배경.pdf) : pdf로 확인
  - YouTube에는 Community가 없어서 Creator에게 개인 블로그를 만들어야 하는 불편함이 존재
  - 기존의 블로그와 차별성 필요
    - | 시간이 지나면 Creator만 확인 가능한 게시글 존재
    - | Youtube의 정보를 가져와서 쉽게 커뮤니티 생성가능
    - | Creator는 Community에 대한 자유도를 가지며 홍보도 가능

- 기대 효과
  - Youtube에 내장되거나, Creator가 유튜브 방송 중에 쉽게 쓸수 있는 게시글로 존재

- 핵심 기능
  - OAuth를 통한 구글 로그인 기능
  - SSE (Server Sends Event)를 활용한 실시간 알림 기능
  - 브라우저 크기별 반응형 웹 페이지
  - 시간이 지나면 사라지는 게시글 존재

---

## 기술 스택

### 💻 Front-end

![Node](https://img.shields.io/badge/Node.js-20.6.1-339933?style=for-the-badge&logo=Node.js&logoColor=fff)
![npm](https://img.shields.io/badge/npm-10.1.0-CB3837?style=for-the-badge&logo=npm&logoColor=fff)
![Next.js](https://img.shields.io/badge/Next.js-13.5.4-000000?style=for-the-badge&logo=Next.js&logoColor=fff)
![typescript](https://img.shields.io/badge/typescript-5.2.2-3178C6?style=for-the-badge&logo=typescript&logoColor=fff)
![tailwind](https://img.shields.io/badge/tailwindcss-3.3.3-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=fff)
![nextui](https://img.shields.io/badge/nextui-2.1.13-000000?style=for-the-badge&logo=nextui&logoColor=fff)
![radixicon](https://img.shields.io/badge/radixicon-2.1.13-161618?style=for-the-badge&logo=radixui&logoColor=fff)
![framer](https://img.shields.io/badge/framer-10.16.4-0055FF?style=for-the-badge&logo=framer&logoColor=fff)
![reactquery](https://img.shields.io/badge/reactquery-4.36.1-FF4154.svg?&style=for-the-badge&logo=ReactQuery&logoColor=white)



### 💻 Back-end

[![JAVA](https://camo.githubusercontent.com/3a1c7dafcdfce483e68f5fb95d057e9421c8109fd105e603542b1ff00fd7ae91/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4a4156412d4646303030303f7374796c653d666f722d7468652d6261646765266c6f676f436f6c6f723d7768697465)](https://camo.githubusercontent.com/3a1c7dafcdfce483e68f5fb95d057e9421c8109fd105e603542b1ff00fd7ae91/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4a4156412d4646303030303f7374796c653d666f722d7468652d6261646765266c6f676f436f6c6f723d7768697465) [![Spring](https://camo.githubusercontent.com/57da5a02a135c27818a618285a57f7e54df63419d1f7ad598905a0bd27e780c7/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f537072696e67626f6f742d3644423333463f7374796c653d666f722d7468652d6261646765266c6f676f3d737072696e67626f6f74266c6f676f436f6c6f723d7768697465)](https://camo.githubusercontent.com/57da5a02a135c27818a618285a57f7e54df63419d1f7ad598905a0bd27e780c7/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f537072696e67626f6f742d3644423333463f7374796c653d666f722d7468652d6261646765266c6f676f3d737072696e67626f6f74266c6f676f436f6c6f723d7768697465) [![Gradle](https://camo.githubusercontent.com/e850f9c862ce515586c3859cab52395f8d096f0de68825fdaaf6b9bea572311e/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f477261646c652d3032333033413f7374796c653d666f722d7468652d6261646765266c6f676f3d677261646c65266c6f676f436f6c6f723d7768697465)](https://camo.githubusercontent.com/e850f9c862ce515586c3859cab52395f8d096f0de68825fdaaf6b9bea572311e/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f477261646c652d3032333033413f7374796c653d666f722d7468652d6261646765266c6f676f3d677261646c65266c6f676f436f6c6f723d7768697465) [![JWT](https://camo.githubusercontent.com/5af78a02d0f7a4b8a759f9580ce718287a0626f80a55c38ad0bac83e0b31f94d/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4a57542d3030303030303f7374796c653d666f722d7468652d6261646765266c6f676f3d6a736f6e776562746f6b656e73266c6f676f436f6c6f723d7768697465)](https://camo.githubusercontent.com/5af78a02d0f7a4b8a759f9580ce718287a0626f80a55c38ad0bac83e0b31f94d/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4a57542d3030303030303f7374796c653d666f722d7468652d6261646765266c6f676f3d6a736f6e776562746f6b656e73266c6f676f436f6c6f723d7768697465) ![Kafka](https://camo.githubusercontent.com/1b371597d577a5f430f0dbc8a356d8951f0b7a6d7dded5eb99e2b4cf1593397f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f6b61666b612d3233314632303f7374796c653d666f722d7468652d6261646765266c6f676f3d6170616368656b61666b61266c6f676f436f6c6f723d7768697465)
![springbatch](https://img.shields.io/badge/springbatch-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![springcloud](https://img.shields.io/badge/springcloud-6DB33F?style=for-the-badge&logo=soundcloud&logoColor=white)

### 💾 DB

![MySQL](https://img.shields.io/badge/MySQL-003545?style=for-the-badge&logo=mysql&logoColor=white)
![AmazonRDS](https://img.shields.io/badge/AmazonRDS-527FFF?style=for-the-badge&logo=AmazonRDS&logoColor=white) <img src="https://img.shields.io/badge/    redis-DC382D?style=for-the-badge&logo=redis&logoColor=white"/>
<img src="https://img.shields.io/badge/S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white"/>


### ⚙CI/CD

[![docker](https://camo.githubusercontent.com/b184cf7adbab9f5464e80c0f5dd32c85393f6248499a57d743e619f4214391c4/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f646f636b65722d3234393645443f7374796c653d666f722d7468652d6261646765266c6f676f3d646f636b6572266c6f676f436f6c6f723d7768697465)](https://camo.githubusercontent.com/b184cf7adbab9f5464e80c0f5dd32c85393f6248499a57d743e619f4214391c4/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f646f636b65722d3234393645443f7374796c653d666f722d7468652d6261646765266c6f676f3d646f636b6572266c6f676f436f6c6f723d7768697465)
<img src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white"/>
<img src="https://img.shields.io/badge/Git Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white"/>
<img src="https://img.shields.io/badge/ArgoCD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white"/>

### 💻 INFRA

<img src="https://img.shields.io/badge/Apache Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white"/><img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white"/><img src="https://img.shields.io/badge/EKS-FF9900?style=for-the-badge&logo=amazoneks&logoColor=white"/><img src="https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white"/>



---

## ✏ 서비스 화면

## 💻 웹

### 커뮤니티


- 커뮤니티 가입

![커뮤니티 가입](https://github.com/TubePlus/.github/assets/140700973/838f3a2d-c8f1-40f8-841d-c29b8baa4a67)

- 커뮤니티, 게시판 생성

![커뮤니티 생성](https://github.com/TubePlus/.github/assets/140700973/40fbd0dd-c876-4720-9d08-3833fcefb196)



## ⚙ 아키텍처

![아키텍처](asset/아키텍쳐.png)

---

## 🧶 유스케이스

![유스케이스](asset/유스케이스.png)

---

## 💾 ERD 다이어그램

![erd](asset/erd.png)

---

## 🔊 API 명세서

##### [API 명세서 링크](https://docs.google.com/spreadsheets/d/1KsbYtnBHnyVvlwZLQ_SGXVpa-z77r8mo/edit#gid=664530878)

---

## 🎞 와이어프레임

![와이어프레임](asset/와이어프레임.png)

---

## 🎟 이벤트스토밍

![이벤트스토밍](asset/이벤트스토밍.png)

---

## 사용자 경험을 향상시키기 위한 노력

### 1. 배포
- AWS를 통한 auto Scale-out
- helm, terraform을 통한 쿠버네티스 구현으로 etc서버 배포
- jenkins-> GitAction + ArgoCD 적용
![쿠버네티스 구현도](asset/aws.png)

- 나머지 서버는 Spring Cloud를 통해 배포
![infra 구성](asset/infra구축도.png)

### 2. 데이터 배치 및 캐싱 처리

- batch를 통한 반복되고 자주 찾는 요소는 cache이용으로 속도 개선
![redis](asset/redis.png)


- 정산되는 자료들을 batch를 통해 page단위로 모아서 처리하고, 한번에 저장해서 쿼리를 단축
- 처리되지 않은 데이터에 대해서 2회 반복해서 신뢰도 향상, 연산되지 않은 데이터 따로 기록
![batch](asset/batch구축도.png)

### 3. 아키텍처

- 헥사고날을 통한 도메인을 web과 service를 port로 분리해서 쉽게 MSA를 할 수 있고, 재사용성 있는 코드를 재현하려고 함
![헥사고날](asset/헥사고날.png)


- 읽기와 쓰기가 다양한 타입이 들어가고, 데이터 양이 많은 게시글을 읽기, 쓰기로 도메인 분리
- DB도 replica를 통해 분리 -> MySQL, MySQLReplica
![CQRS](asset/cqrs.png)

