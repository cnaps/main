# 시냅스 방법론 3.0
> 시냅스 방법론 3.0 의 공정 및 주요 산출물, 샘플코드를 공유한다.



# SW Moderization 공정도




# 네이티브 공정도

![공정도](https://github.com/cnaps/main/blob/master/img/%EA%B3%B5%EC%A0%95%EB%8F%84.png)  

# 프렉티스 별 주요활동 & 산출물 
|Phase|Practice | Step | Output |
|------|------|---|---|
|Sprint0|외부아키텍처정의|- 인프라정의<br>- 플랫폼정의<br>- 백엔드서비스정의<br>- 배포정책정의|인프라구성도<br>아키텍처구성도<br>배포구성도|
|Sprint0|내부아키텍처정의|- 프론트엔드기술정의<br>- 서비스내부구조정의<br>-비지니스로직구조설계<br>-데이터매핑구조설계<br>|서비스별패키지구조<br>기타아키텍처문서|
|Sprint0|구현환경정의|-개발환경정의<br>-테스트환경정의<br>-운영환경정위|클라우드 개발/테스트/운영환경|
|Sprint0|마이크로서비스도출|||
|Sprint0|서비스스펙(SPEC)정의|||
|Sprint0|테스트계획수립|||
|Sprint0|데이터이행계획수립|||
|SprintN#|마이크로서비스모델링|||
|SprintN#|UI설계|||
|SprintN#|프론트엔드구현|||
|SprintN#|지속적통합|||
|SprintN#|지속적배포|||
|SprintN#|데이터이행리허설|||
|Test&Release|통합테스트|||
|Test&Release|성능테스트|||
|Test&Release|데이터이행|||
|Test&Release|릴리즈|||


# 주요 ASSET
## 0.아키텍처 
- 아키텍처 구성도
  - 외부 아키텍처
    - 배포 구성도 
    - 쿠버네티스 기반 
  - 내부 아키텍처 
    - 헥사고널 & 클린아키텍처 

## 1.설계
- 마이크로서비스도출
  - 컨텍스트맵
    - DDD 전략적설계 개념
    - 이벤트스토밍가이드
    
- 마이크로서비스설계 
  - 내부구조정의 
    - 헥사고널 아키텍처 적용 패키지구조
    - 단순 CRUD구조와 도메인모델구조 선택가이드
  - API설계서
    - API 설계 개념  
  - 도메인모델
    - DDD 전술적설계 개념
  - 데이터모델 
## 2.개발
- 내부영역개발
  - 도메인 구현
  - 레파지토리 구현
  - 서비스 구현
  - 도메인이벤트 구현
- 외부영역개발
  - 컨트롤러 구현
- EDA구현
  - 도메인이벤트 어댑터 구현
    - 카프카 설치
- CQRS구현
    
## 3.통합 및 배포
- 도커라이징
  - DockerFile
- 컨테이너라이징
  - 쿠버네티스 아키텍처의 이해
  - 실습
- 배포파이프라인구축
  - 애저
  - AWS

## 컨텐츠 및 교육교재
  - [MSA개념 및 주요패턴](https://engineering-skcc.github.io/tags/microservice/)
    - [마이크로서비스 개념](https://engineering-skcc.github.io/categories/#microservice-%EA%B0%9C%EB%85%90)
    - [마이크로서비스 Outer 아키텍처](https://engineering-skcc.github.io/categories/#microservice-outer-achitecture)
    - [마이크로서비스 Inner 아키텍처](https://engineering-skcc.github.io/categories/#microservice-inner-achitecture)
    - 교육교재 
  - 마이크로서비스 모델링
    - 도메인주도설계
      - 전략적설계
      - 전술적설계
    - API설계
    - 이벤트스토밍
    - 교육교재
   


