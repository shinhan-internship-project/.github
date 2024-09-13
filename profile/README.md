# WePB
> 고객-PB간 일정 관리 및 채팅 서비스  
> `신한투자증권 인턴` 공통 프로젝트

## Service Introduction
PB나 고객 입장에서 다음과 같은 불편함을 느낀다고 조사되었습니다.

[PB 입장]
> 🙋🏻‍♂️ "오늘은 어떤 고객이랑 상담이지??😅"<br> 
> 🙋🏻‍♀️ "내일은 휴가여서 상담이 불가능한데 어떻게 내가 휴가라는 것을 알리지?"<br>
> 🙋🏻 "다른 고객님과 전화상담 중에 놓치는 전화들이 너무 많아😥"<br>

[고객 입장]
> 🙋🏻‍♂️ "배정된 PB가 어떤 사람인지 모르겠어... 😅"<br> 
> 🙋🏻‍♀️ "PB 정보를 찾아보고, 내 자산을 맡길 PB를선택하고싶어"<br>
> 🙋🏻 "온라인으로 간편하게 상담을 신청하고 싶어😥"<br>

💬 WePB을 통해 사용자는
- 고객이 `PB의 정보와 전문성을 확인`하고
- 메신저를 통해 간편하게 `상담을 예약`하며
- `PB의 업무 효율성`을 높일 수 있습니다.

## ERD
<img width="600" src="https://github.com/user-attachments/assets/eb81f7d6-4864-4eb7-a82f-de59bfe6e447">

## Project Architecture
<img width="600" src="https://github.com/user-attachments/assets/c1dd2bac-f06f-4ad6-8804-197dafd04b89">

## Team Member
|권기현|김예리|신의진|이한슬|허상진|
|:---:|:---:|:---:|:---:|:---:|
|<img width="160px" src="https://avatars.githubusercontent.com/u/99806443?v=4"/> |<img width="160px" src="https://avatars.githubusercontent.com/u/46741373?v=4" />|<img width="160px" src="https://avatars.githubusercontent.com/u/150140536?v=4" />|<img width="160px" src="https://avatars.githubusercontent.com/u/129421334?v=4" />|<img width="160px" src="https://avatars.githubusercontent.com/u/128025654?v=4" />|
|[@kkh0331](https://github.com/kkh0331)|[@rlafl7942](https://github.com/rlafl7942)|[@Tomk2d](https://github.com/Tomk2d)|[@eehanseul](https://github.com/eehanseul)|[@bookeers](https://github.com/bookeers)|
|Calendar Page<br/>MyPage<br/>실시간 통신 연결|Main Page<br/>Chat Pae<br/>전체 UI/UX 구성|실시간 통신 연결<br/>Chat API<br/>Main Page API<br/>아키텍처 설계<br/>DB 설계<br/>인프라 및 배포|DB 설계<br/>User API<br/>Main API<br/>Document API<br/>Calendar API|Login Page<br/>회원가입 Page<br/>PB 데이터 생성|

## Main Features
### ⭐️ 메인 페이지
- 카테고리 분류를 통한 PB 조회
- 투자 전략 필터링을 통한 PB 조회
- 거리순 정렬을 통한 PB 조회
- PB 리스트(무한 스크롤)
- PB 상세보기

### ⭐️ 캘린더 페이지
- 캘린더를 통해 일정 있는 날 한 눈에 확인 가능
- 체크된 날짜의 일정 확인 가능
- 일정의 상세 내용 확인 가능
- PB 개인 일정 추가

### ⭐️ 채팅 페이지
- 채팅방 리스트 확인 가능
- 실시간 채팅 가능
- 알람 기능 제공
- PB 상담 예약 신청 가능

### ⭐️ 마이 페이지
- 상담 요청 내역 확인 가능

### ⭐️ 로그인/회원가입 페이지
- 고객은 회원가입을 통해 서비스 이용 가능
- PB는 바로 로그인 가능

## Screen Configuration
|메인 페이지|PB 상세 보기|캘린더 페이지|개별 일정 추가|채팅 리스트|
|:---:|:---:|:---:|:---:|:---:|
|<img width="150" src="https://github.com/user-attachments/assets/87df6bf8-25f7-4796-82e7-7d7ad1c6e52f">|<img width="150" src="https://github.com/user-attachments/assets/3ac9a807-59c7-4af7-83a5-334431214c96">|<img width="150" src="https://github.com/user-attachments/assets/364b1191-dedc-4dd6-846c-9a0a05e9864d">|<img width="150" src="https://github.com/user-attachments/assets/cf8d66f1-8ab9-4d77-a235-a2d28d52b4d2">|<img width="150" src="https://github.com/user-attachments/assets/58af320d-918d-423a-b34f-a04f92f002eb">|

|실시간 채팅|상담 예약|마이페이지|로그인|회원가입|
|:---:|:---:|:---:|:---:|:---:|
|<img width="150" src="https://github.com/user-attachments/assets/562f4757-baa6-4ddd-8a09-cad3ec3ffe92">|<img width="150" src="https://github.com/user-attachments/assets/38ada505-eb57-4c5f-a890-370b5f4b6875">|<img width="150" src="https://github.com/user-attachments/assets/86c5bd4a-d360-4f91-8df7-a827dc5b6bf9">|<img width="150" src="https://github.com/user-attachments/assets/691e48ed-ae84-4ba1-bf73-0d91cf7f6e34">|<img width="150" src="https://github.com/user-attachments/assets/0b9e2f69-4d30-4516-ae7a-0f20948b28a7">|
