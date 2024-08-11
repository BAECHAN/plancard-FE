# plancard-FE
여행지 카드 수집 애플리케이션 FE

## 개요
여행지 카드 수집 애플리케이션은 여행을 좋아하는 사람들에게 흥미롭고 유용한 기능을 제공할 수 있는 멋진 아이디어입니다. 이 애플리케이션의 주요 기능을 다음과 같이 정리하고 추가적인 세부 사항을 포함해보겠습니다.

### 주요 기능

1. **여행지 카드 컬렉션 관리**
    - **카드 수집**: 사용자는 여행을 통해 다양한 여행지 카드를 수집할 수 있습니다.
    - **카드 정보**: 각 카드에는 해당 여행지의 사진, 설명, 위치 정보 등이 포함됩니다.
    - **카드 관리**: 사용자는 자신이 보유한 카드를 컬렉션 형태로 관리할 수 있습니다.
    - **카드 등급**: 카드의 희귀성이나 획득 난이도에 따라 등급을 부여할 수 있습니다 (예: 일반, 희귀, 전설).

2. **일정 계획 및 공유**
    - **타로카드처럼 일정 짜기**: 사용자는 여행지 카드를 기반으로 일정 계획을 세울 수 있습니다. 카드를 드래그 앤 드롭하여 일정을 구성하고, 각 여행지 방문 시간을 설정할 수 있습니다.
    - **일정 공유**: 계획한 일정을 다른 사용자와 공유할 수 있습니다. 공유된 일정은 다른 사용자가 참고하거나 자신의 일정에 추가할 수 있습니다.
    - **여행지 추천**: 일정을 세울 때, 방문한 적 없는 주변의 인기 여행지를 추천받을 수 있습니다.

3. **위치 기반 여행지 카드 획득**
    - **위치 인증**: 사용자가 특정 위치에 접근하면, 해당 위치의 여행지 카드를 획득할 수 있습니다. 위치 인증은 GPS를 기반으로 하며, 해당 위치에 실제로 방문해야 카드가 지급됩니다.
    - **무료 카드 획득**: 사용자가 여행지 카드를 가지고 있지 않더라도, 특정 위치에 접근하면 무료로 카드를 획득할 수 있습니다.
    - **이벤트 카드**: 특정 이벤트나 기간 동안만 획득할 수 있는 한정판 카드를 제공하여 사용자 참여를 유도할 수 있습니다.

### 추가 기능 및 고려사항

- **사용자 프로필 및 업적 시스템**: 여행을 많이 다닌 사용자에게 보상이나 업적을 제공하여 참여를 유도합니다.
- **커뮤니티 기능**: 사용자가 서로 여행지 정보를 공유하고, 리뷰나 팁을 남길 수 있는 커뮤니티 기능을 추가합니다.
- **알림 기능**: 사용자가 특정 여행지에 가까워졌을 때 카드 획득 알림을 받도록 설정할 수 있습니다.
- **오프라인 모드**: 여행 중 인터넷 연결이 어려운 경우를 대비하여 오프라인에서도 카드 정보를 볼 수 있도록 합니다.

## 기술

### 백엔드

1. **프로그래밍 언어**: Python, JavaScript (Node.js), Java, Kotlin
2. **웹 프레임워크**: 
    - Python: Django, Flask
    - Node.js: Express.js
    - Java: Spring Boot
    - Kotlin: Ktor
3. **API 개발 및 관리**: RESTful API, GraphQL
4. **인증 및 권한 관리**: JWT, OAuth
5. **실시간 데이터 처리**: WebSockets, Socket.io

### 프론트엔드

1. **프로그래밍 언어**: JavaScript, TypeScript
2. **프레임워크 및 라이브러리**:
    - React.js
    - Vue.js
    - Angular
3. **상태 관리**: Redux, Vuex, MobX
4. **UI 라이브러리**: Material-UI, Bootstrap, Ant Design

### 모바일 앱 개발

1. **프로그래밍 언어**:
    - Java, Kotlin (Android)
    - Swift (iOS)
2. **크로스 플랫폼 프레임워크**:
    - React Native
    - Flutter
    - Ionic

### 데이터베이스

1. **관계형 데이터베이스**: PostgreSQL, MySQL, SQLite
2. **NoSQL 데이터베이스**: MongoDB, Firebase Firestore
3. **인메모리 데이터베이스**: Redis

### 위치 기반 서비스

1. **지도 API**: Google Maps API, Mapbox
2. **위치 서비스**: GPS, Geolocation API

### 기타 도구 및 서비스

1. **클라우드 서비스**: AWS, Google Cloud, Microsoft Azure
2. **서버 관리**: Docker, Kubernetes
3. **CI/CD**: Jenkins, GitHub Actions, Travis CI
4. **버전 관리**: Git, GitHub, GitLab, Bitbucket
5. **테스트**:
    - 프론트엔드: Jest, Mocha, Cypress
    - 백엔드: pytest, JUnit, Mocha/Chai
6. **분석 및 모니터링**: Google Analytics, New Relic, Sentry
7. **디자인 도구**: Figma, Adobe XD, Sketch

### 기술 스택 예시

#### 백엔드
- **언어**: Python
- **프레임워크**: Django (REST framework 사용)
- **데이터베이스**: PostgreSQL
- **인증**: JWT
- **실시간 데이터**: Django Channels

#### 프론트엔드
- **언어**: JavaScript, TypeScript
- **프레임워크**: React.js
- **상태 관리**: Redux
- **UI 라이브러리**: Material-UI

#### 모바일 앱
- **프레임워크**: React Native

#### 클라우드 및 기타
- **클라우드 서비스**: AWS (EC2, S3, RDS)
- **버전 관리**: GitHub
- **CI/CD**: GitHub Actions
- **지도 API**: Google Maps API

============================================================================================================================================================================================================

## 컨텐츠 목차

- 카드
- 플랜
- 마이페이지
- 로그인 & 회원가입
- 친구 ( 추후 )
- 카드 탐험
- 플랜 탐험

## 컨텐츠 용어
- 카드 
- 덱 ( 카드 뭉치 - '내 카드 목록' )
- 브릿지 ( '플랜' 에서 '카드'와 '카드'를 이어주는 역할 )
- 플랜 ( '카드' 와 '브릿지'를 활용하여 계획을 작성 )

## 컨텐츠 요약 및 우선순위

카드목록 필터
카드목록 정렬
카드목록 검색
카드스크랩된 카드목록 정렬
스크랩된 카드목록 검색
스크랩된 카드목록 페이징
카드 상세 
목록 페이징

스크랩된 카드목록 필터



## 컨텐츠 상세

1) 카드
   - 카드 목록 
	 - 필터  -> 역순 포함
		- 나라별
		- 도시별
		- 등급별 ( 이벤트 카드 / 1~5별 )
		- 테마별 ( 랜드마크 / 음식점 / 가게 / 공공시설 등 )
		- 보유유무별
		- 획득날짜별( 캘린더 ) 
		  
     - 정렬  -> 역순 포함
		- 이름순
	    - 나라순
	    - 나라 안에 도시순
	    - 등급순
	    - 테마순
	    - 보유순
	    - 획득날짜순
     - 검색
		- 제목
		- 상세
     - 페이지네이션 ( 무한스크롤 )

   - 스크랩된 카드 목록 
     - '카드 목록'과 기능은 동일함
   - 카드 상세 
     - 이름
     - 요약
     - 등급
     - 나라 ( 도시 & 지역 )
     - 테마
     - 보유유무
     - 획득날짜
     - 이미지
     - 커스텀이미지
     - 설명
     - 운영시간 ( 선택 )
     - 비용( 입장료 / 가게 대표 메뉴 or 사용자 통계 - 구글 지도에서 보여주는 인당 비용 같은 ) (선택)
     - 구글지도 링크 
     - 추가설명 ( 사용자가 위키처럼 등록 시 관리자가 검증 후 반영 ) (선택)
       
     - 카드 앞뒷면 전환 ( 눌렀을 때 오른쪽 사이드바에 화면 크게 나오는거도 괜찮을듯 )
     - 카드 편집
        - 카드 커스텀 이미지 추가 및 대표 이미지로 등록
	 - 카드 스크랩
	 - 카드 지도 ( 구글지도와 별개 )
	 - 

2) 플랜
   - 플랜 목록
     - 필터
	    - 날짜별 ( 캘린더 )
	    - 상태별 ( 예정 / 진행 / 완료 / 보류 )
	    - 태그별 ( 본인이 정한 )
	- 검색
		- 제목
		- 설명
	- 설정
	    - 공유 / 수정 / 삭제
   - 플랜 상세
	- 제목
	- 설명 
	- 태그 
	- 작성자 ( 퍼오기 기능 및 '탐험' 시 필터용 )
	- 등록날짜
	- 수정날짜
	- 좋아요 수
	- 스크랩 수
	- 기간별 ( 예시. 3박 5일 or 4일 )
	- 경유지 수 ( 제한 이 있어야 되나 )
	- 
    - 플랜 위치 변경
		- 드래그앤드랍 ( 직접 들고 이동 )
		- 순서변경버튼 ( 맨앞으로가기 / 맨뒤로가기 / 앞으로가기 / 뒤로가기 )
	- 카드 상세 / 카드 수정 
	    -  '소유한 카드의 커스텀 정보' 를 가져옴,
		   '플랜'에 속한 카드의 '커스텀 정보'를 수정하면 '소유한 카드의 커스텀 정보'와 별개로 
		   해당 '플랜' 에서만 사용되는 '커스텀 정보'임
	- 브릿지 ( string만 등록 가능 )
		- 등록
		- 수정 
		- 삭제
		- 보기

3) 카드 탐험
   - 필터
        - 나라별
        - 도시별
        - 태그별

   - 검색
   - 추천
  
4) 플랜 탐험
   - 필터
	- 날짜별 ( 캘린더 ) - 등록날짜로? 수정날짜로?
        - 기간별
   - 검색
	- 작성자
	- 제목
	- 태그

5) 마이페이지 및 로그인&회원가입
   - 로그인
   - 회원가입
   - 마이페이지
   - 아이디찾기
   - 비밀번호 재발급
   
## 권한


1) 카드
- 편집권한 ( 본인 )
- 보기권한 ( 본인을 포함한 보기권한이 있는 유저 )

2) 플랜

- 편집권한 ( 본인 및 수정 권한이 있는 사용자)
- 보기권한 ( 본인을 포함한 보기권한이 있는 유저)

3) 사용자정보
   - 편집권한 및 보기권한 모두 ( 본인 )

4) 탐험
- 권한 시스템 적용 x
