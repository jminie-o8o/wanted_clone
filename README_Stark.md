  # 개발일지
  ## 2021-10-30
 
  - 최초 회의 100%  
  - 기획서 작성, 수정  
  - 서브 도메인 주소 dev, prod로 수정  

  ## 2021-10-31
  
  - 원티드 웹 분석
  - ERD 초안 구축

  ## 2021-11-1
  
  - ERD초안에 대한 will 님과 미팅
  - 프로젝트 보드 생성
  - GitHub 컨벤션 정하기
  - 서버 구축

  ## 2021-11-2
  
  - ERD 최종 마무리 (will 님과 미팅)
  - API 초안 작성
  - 아키텍쳐 구조 회의


  ## 2021-11-3
    
   ### ERD 수정 
   - DB int타입 Long(BIGINT)타입으로 변경
   - 스킬 부분 매핑 따로 구현
   - 자동로그인 부분 구현, 회원 테이블에 자동로그인 여부 체크 컬럼에 추가
   - null값 부분 처리
   
   ### API 명세서 구체화
   - 윌, 스타크 명세서 구분 작성(색으로 구분)
   - DELETE로 API 명세 후, 로직은 update로
   - URI 하이푼 구분자 넣기
   - API 선별 → 우선순위를 부여. 원티드 서비스 기능을 파악하고 그 서비스 우선순위에 맞게 API를 분류
   - API 배분 → 난이도별 , 기능별 등 기준 세우기


## 2021-11-4

  ### 회원가입 API 구현
  - 회원가입 API 구현
  - 유저 기본 정보 조회 API 구현
  - 유저 기본 정보 수정 API 구현



## 2021-11-5

  
  ### 회원탈퇴 및 채용공고 API 구현
   - 회원 탈퇴 API 구현
   - 채용공고 등록 API구현

## 2021-11-6

  ### 채용공고 API
  - 채용공고 페이지 조회 (쿼리스트링 이용)
  - 채용공고 페이지 상세 (DTO를 이용해 객체 안에 객체를 넣어 좋아요 수와 회사 이미지 그리고 PostRes를 함께 담아줌)
  - 채용공고 수정
  - 채용공고 좋아요
  - 채용공고 북마크

## 2021-11-7

  ### 채용공고 마무리
  - 채용공고 좋아요 취소
  - 채용공고 북마크 취소
  - 더미 데이터 관련 회의 


## 2021-11-8

  ### 이력서 API
  - 이력서 생성 API
  - 데이터 싹 지우고 더미데이터 생성
  - 2차 피드백 전 API 명세서 작성
  
  
## 2021-11-8
  
  ### 이력서 API
  - 이력서 생성 API
  - keyholder를 이용하여 생성된 Resume index를 바로 이용해 매핑된 다른 테이블에 이용할 수 있게 구현
  - 더미데이터 추가