# SmartReptileCage
텐서플로 기반의 영상처리 기술을 활용한 스마트 도마뱀 사육장    


## 시스템 구성도
<img src="https://user-images.githubusercontent.com/47026817/155682381-1535a62c-d45d-4351-b166-a0bcc9933bc5.png"/>


## SW 구성 
- **도마뱀 활동 기록** : 
  - Tensor flow를 사용한 도마뱀 인식
  - 도마뱀 위치 좌표를 활용해 일간/주간 활동량 계산 및 시각화
  - 사육장 내 도마뱀 위치 빈도 측정 및 시각화
- **사용자 위치기반 주변 병원 표시**:  
  - 도마뱀 병원 표시
  - 가까운 병원 검색
  - 병원 전화 연결 및 정보 확인
- **라즈베리파이(사육장) - 앱 연결** 
  - 주변 블루투스 장비 검색
  - 서버와 클라이언트간 블루투스 데이터 통신
  - 블루투스 자동 페어링 
  - 블루투스 자동 세팅   
- **데이터 관리** 
  - 사용자 정보
  - 자유게시판
  - 영상 정보
  - 사육 정보
  - 센서 정보
- **기타** 
  - 로그인 / 회원가입
  - 먹이 급여
  - 커뮤니티
  - 환경설정



## 개발환경
- **Server** : Apache Tomcat 8.0
- **Language** : Java, C
- **DBMS** : MySQL 5.7
- **Tool** : Eclipse, Android Studio
- **OS** : Window 10
- **Raspberry** : raspbian stretch
- **API** : Google Map, JDBC





<img src="https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white"/> <img src="https://img.shields.io/badge/Tensorflow-FF6F00?style=flat-square&logo=TensorFlow&logoColor=white"/> <img src="https://img.shields.io/badge/ApacheTomcat-F8DC75?style=flat-square&logo=Apache Tomcat&logoColor=white"/> <img src="https://img.shields.io/badge/Raspberry Pi-A22846?style=flat-square&logo=Raspberry Pi&logoColor=white"/>   
<img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=Java&logoColor=white"/> <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=Python&logoColor=white"/> <img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=C&logoColor=white"/> <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=MySQL&logoColor=white"/>
