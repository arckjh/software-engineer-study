# software-engineer-study
소프트웨어 엔지니어가 되기 위한 스터디 정리 

### 데이터
* 비트와 바이트
* 2진수 / 10진수 / 16진수
* 정수 / 부동소수점
  - int, float, double
* 문자열 인코딩
  - ASCII (American Standard Code For Information Interchange) : 7bit / 128개 문자
  - ANSI (American National Standard Insitute) : 8bit / 256개 문자
  - UNICODE : 2byte / 전 세계 문자
  - UTF-8 : 멀티바이트(1~4byte) / 전 세계 문자(가변 길이 문자)
  
### 컴퓨터 구조
* 하드웨어 구조    
![하드웨어 구조 이미지](https://t1.daumcdn.net/cfile/tistory/1847673B4DC0E57C18)   
   
### OS 컨셉
* 커널   
![커널 이미지](https://t1.daumcdn.net/cfile/tistory/22642A4D56C3D67811)
* 프로세스
  - 메모리 구성   
  ![메모리 구성](https://lh3.googleusercontent.com/proxy/mZH4wYKAGIrU6lkSXkRTtlFNcXN12OJx_NPscVQhiOIZbdWSGYyPtx-qWBrynhtCbZMpeQLuwE7AhbvMDEVQ4N0GQZcbOrox21nvjkJnk288KmMyDQZNqSb1y1ktD97Ou1DNa3FU6UVjjSpJHYfJkBwC-S3LANUlX-1k8Gq3EZiY7dX1UjPi2GWMU_k9rKKTX8h-7i4wHQynUZ9sVGmF-fZCkNNzm1khiE-KL0iu8zDerq9WdrH0IvYQ-IXXPrQeAkgzQ7nng_RDo2GimSXLeDPkl6FmLd1RVYeq5xWoMJ4)
  - 스케쥴러 & 인터럽트
  ![스케쥴러 이미지](https://wkdtjsgur100.github.io/images/posts/process-status.png)
  - 컨텍스트 스위칭   
  ![컨텍스트 스위칭](https://t1.daumcdn.net/cfile/tistory/263A504B560486D324)
  - 세마포어   
  ![세마포어 이미지](https://t1.daumcdn.net/cfile/tistory/231BDE45594D0B552E)
  - IPC   
  ![IPC 이미지](https://t1.daumcdn.net/cfile/tistory/99B096385C4C756932)
* 쓰레드
  - 기본 개념   
  ![쓰레드 이미지](https://t1.daumcdn.net/cfile/tistory/99195A495BA7B8EE08)
  - 뮤텍스(임계 영역)
  ![뮤텍스(임계 영역) 이미지](https://prepinsta.com/wp-content/uploads/2019/01/Mutex-Vs-Semaphore-1-1024x429.png)
* 메모리 개념   
![메모리 개념 이미지](https://lh3.googleusercontent.com/proxy/5swmt6p4H3WsMmUQ8jkjIbIYumGRMzIyblfqU61SWaKpuaXEl4jQh_gGCr1Zvfuuys2LVKU_jH6k9hSh3V0wHorsls77AulLDvHf-yr1CaLE3abLQsVemmv5OLdzCDe7POrOhwKPP4ruBBqdFHkWMAirpv2z3lNNLSY)
* 파일 시스템   
![파일 시스템 이미지1](https://lh3.googleusercontent.com/proxy/mXNhkIJe_NInWvXb46LfLAF85_SaykmtaqyteQPTf8mVk7l_Vkfbjcg4_HFM45nEFCXF5BcXQjiJBr487FTYXnxWTYO37-IVsbJCz0llgKTEWTxUigphZ-3OXSY0rxl-IbkH7zrVfv6LrTPAG-d6TMPVaFVX9rhe0UrnGOMRDpV7)
![파일 시스템 이미지2](https://kouzie.github.io/assets/OS/OS_12_8.png)
* 네트워크
  - OSI 7계층   
  ![OSI 7계층 이미지](https://img1.daumcdn.net/thumb/R720x0.q80/?scode=mtistory2&fname=http%3A%2F%2Fcfile21.uf.tistory.com%2Fimage%2F995EFF355B741790359A2E)
  ![OSI 7계층 이미지2](https://lh3.googleusercontent.com/proxy/QuhSiqJOLD7VaN2dsBrH36RGSmFPBW8ptoenkyQ_VPrkd-7hGudoN7P2y5iNAKo82XS5AgV4jYETN6FF-jQLgRE8Io7LyXvjZh3sFa5hODnXDbmY9zmx5U-sp9cTBLz-Le4uqKfj_qCKheC91X8Cm4mOTn39y44)
  - TCP/UDP 차이점
    + 3way handshake란?
* IO : 동기/비동기 & 블럭/논블럭   
![동기/비동기 and Block/Non-Block 이미지](https://i.imgur.com/oPYfrZl.png)
  - 동시성과 비동기의 차이점은??
* 리눅스 기본 구조   


### 개발 방법론
* 자료구조
  - 배열
  - 리스트
  - 스택(LIFO)
  - 큐(FIFO)
  - 우선순위 큐
  - 해시 테이블
  - 트리
  - 그래프
* 알고리즘   
  ![알고리즘 이미지](https://i.imgur.com/EPdDmwQ.jpg)
  - 정렬
    + 선택 정렬
    + 버블 정렬
    + 카운트 정렬
    + 퀵 정렬
    + 병합 정렬
  - 재귀 함수 사용법
  - 메모리제이션
* 백엔드
  - HTTP 프로토콜 이해
  - REST API 설계
* 개발 설계
  - 클린코드
  - OOP
    + SOLID
    + 중요 패턴 : [생성] 싱글턴, 팩토리 메소드 || [구조] 데코레이터, 파샤드 || [행위] 커맨드, 이터레이터, 옵저버, 상태, 전략, 템플릿 메소드
  - TDD
    + 유닛 / 기능 / 통합 테스트
    + 코드 정적 분석
  - DDD
    + 객체 라이프 사이클 및 유비쿼터스 언어 사용
    + entity/value
    + aggregation
    + factory
    + service
    + repository
 
### 미들웨어
* 웹서버 : 아파치 / NGINX
  - 동기/쓰레딩 방식   
  ![동기/쓰레딩 방식](https://mblogthumb-phinf.pstatic.net/MjAxNzAzMjZfMTI2/MDAxNDkwNDk1NjMxNzU4.wrfzv-j7_pzF4GorDTt52dZPzLcUPwnu6JJkgvD53r0g.2xqzw_4Z557pZPaKMbg5pCF3CfvyQtpBqnZrA1p9qjYg.GIF.jhc9639/mighttpd_e01.gif.gif?type=w800)
  - 비동기/이벤트 드리븐 방식   
  ![비동기/이벤트 드리븐 방식](https://mblogthumb-phinf.pstatic.net/MjAxNzAzMjZfMTM3/MDAxNDkwNDk1NjMxNzgy.OHZ33nerX_6Hc92Mg_xjr51acwwi1P_mq3SIl7Cuhisg.niRsQQVM5CwGpXKcdOxl3bkNsmfBkqGV1ajcBpV6CvQg.GIF.jhc9639/mighttpd_e02.gif.gif?type=w800)
* 데이터베이스
  - 1,2,3 정규화  
  - EER 다이어그램
  - 실행 계획
* 인메모리 캐시 : 레디스, 맴캐시
* Nosql : MongoDB, couchbase
* 검색엔진 : Elasticsearch

### 데브옵스
* 클라우드 관리
* GIT Flow
* CI/CD
* 컨테이너 가상화
* 로그 수집 및 분석
