# 🏋🏻GymCarry Project🏋🏻

### 비트캠프 파이널 프로젝트
</br>
- Website : http://ec2-3-144-47-221.us-east-2.compute.amazonaws.com:8080/gym/index
</br>
- Work Repository : https://github.com/alghrksl/Carry
</br>


#### 프로젝트 소개 
  > 운동을 하고 싶지만 막상 알아보기는 귀찮은 사람들,   
    퍼스널트레이닝을 받고싶은데 센터 영업은 싫지만 나와 꼭 맞는 선생님은 찾고 싶은 사람들을 위해 만든    
    웹 기반의 일반회원(멤버) - 트레이너(캐리) 1 : 1 매칭 프로그램
    </br>
    </br>
  🤝 팀 구성 : 6명    
  📆 2021/08 - 2021/09   
  👉 내 사용 기술(Front) : HTML5, CSS3, JavaScript, jQuery, Ajax    
  👉 내 사용 기술(Server) : Java, Spring, mybatis, MySQL, Python   
  👉 내 사용 기술(API & etc) : KAKAO MAP, jQuery UI, CKEditor / AWS EC2, AWS RDS, MySqlWorkBench, STS, Visual Studio Code
  
</br>

- **담당 기능**
  * **Index**
      > **Frontend & Backend**   
      > - 일반 회원과 캐리 회원의 출력 메뉴에 분기처리를 하여 다르게 노출 구현   
      > - 캐리 리뷰는 Swiper.js를 사용하여 슬라이드 형식으로 구현했고, 최신순으로 10개 출력
  * **About**
      > **Frontend**   
      > - 프로젝트에 관한 간단한 소개가 있고, 팀원들의 미모티콘을 클릭시 당사자의 깃허브로 이동
  * **Place**
      > **Frontend & Backend**   
      > - 헬스장, 필라테스, 요가업체의 데이터를 출력하는 페이지   
      > - 프로젝트에서 요구하는 정보에 충족하는 제공 데이터가 없어 파이썬을 사용하여 네이버 플레이스에서 크롤링하여 필요한 정보 데이터만 추출   
      > - 전체, 헬스, 필라테스, 요가로 카테고리 구분   
      > - KAKAO MAP API를 사용하여 추출한 데이터의 좌표값으로 마커를 출력했고, 해당 마커를 클릭시엔 하단 플레이스 리스트에 해당하는 플레이스 박스로 스크롤 이동하도록 구현   
      > - jQuery UI Autocomplete를 사용하여 자동완성 검색 기능을 구현   
      > - 입력한 키워드를 기준으로 자동완성되는 리스트가 하단에 출력되며, 선택한 자동완성 검색어를 클릭시에 해당 플레이스 상세 페이지로 이동되도록 구현   
      > - 상세페이지 : 플레이스의 상세 정보가 출력되며, 우측에 사이드 윙 배너 형식의 박스가 스크롤 위치에 맞춰 따라다니도록 구현
  * **Community**
      > **Frontend & Backend**  
      > - 좋아요/댓글 기능 구현(비동기처리)   
      > - CKEditor를 사용하여 이미지, 링크 등 다양한 기능 제공
      > - 게시글 상세 페이지 구현
      > - 게시글 수정/삭제
      > - Session을 이용해서 글 작성 접근 제한   
      > - Session을 이용해서 좋아요/댓글 기능 제한   
      > - Session을 이용해서 게시글 수정/삭제 버튼 노출 여부 분기처리   
      
  * **My Page(Carry) _ 기본정보수정 / 내 회원 리스트**
      > **Backend**
      > - 캐리 기본 정보 수정 구현
      > - 해당 캐리를 결제한 회원 리스트 출력
 </br>
  
- **ERD**
  ![erd](https://user-images.githubusercontent.com/70023536/135314352-610a2a55-cbc5-4f3a-b4b7-cc10f8d96af2.png)
</br>

- **Test 계정**
  - Member : tmdals1@naver.com / 1234   
  - Carry : tmdals1@nate.com / 1234
  - Admin : admin / admin
