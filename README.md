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
![하드웨어 구조 이미지2](https://t1.daumcdn.net/cfile/tistory/263A504B560486D324)
   
### OS 컨셉
* 커널   
![커널 이미지](https://t1.daumcdn.net/cfile/tistory/22642A4D56C3D67811)
* 프로세스
  - 메모리 구성   
  ![메모리 구성](https://rookieboxsite.files.wordpress.com/2017/10/c_memmap_exam_vs.png?w=648)
  - 스케쥴러 & 인터럽트
  ![스케쥴러 이미지](https://wkdtjsgur100.github.io/images/posts/process-status.png)
  - 컨텍스트 스위칭   
  ![컨텍스트 스위칭](https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=http%3A%2F%2Fcfile28.uf.tistory.com%2Fimage%2F9924B24F5BB1BAD912D938)
  - 세마포어   
  ![세마포어 이미지](https://t1.daumcdn.net/cfile/tistory/231BDE45594D0B552E)
  - IPC   
  ![IPC 이미지](https://t1.daumcdn.net/cfile/tistory/99B096385C4C756932)
* 쓰레드
  - 기본 개념   
  ![쓰레드 이미지](https://t1.daumcdn.net/cfile/tistory/99195A495BA7B8EE08)
  - 뮤텍스(임계 영역)
  ![뮤텍스(임계 영역) 이미지](https://prepinsta.com/wp-content/uploads/2019/01/Mutex-Vs-Semaphore-1-1024x429.png)
  - 데드락
  ![데드락 이미지](https://cdn.crunchify.com/wp-content/uploads/2013/07/Java-Thread-Lock-Example-by-Crunchify.jpg)
    + 자원에 대한 동시 접근 불가
    + 자원 점유 기다리고, 대기
    + 자원을 뺏어오지 못함
    + 순환 형태로 대기
  - 쓰레드 풀   
  ![쓰레드 풀](https://t1.daumcdn.net/cfile/tistory/231B374B595F67F43A)
* 가상 메모리   
![가상 메모리](https://mblogthumb-phinf.pstatic.net/20160606_142/yeop9657_1465204023522CTEsY_PNG/%B1%D7%B8%B28.png?type=w2)
![가상 메모리2](https://mblogthumb-phinf.pstatic.net/20160606_24/yeop9657_1465204024106gSiyI_PNG/%B1%D7%B8%B29.png?type=w2)
* 파일 시스템   
![파일 시스템 이미지1](https://t1.daumcdn.net/cfile/tistory/214BAE4956AF0B0E01)
![파일 시스템 이미지2](https://t1.daumcdn.net/cfile/tistory/2468C83E56AF0ED719)
![파일 시스템 이미지3](https://kouzie.github.io/assets/OS/OS_12_8.png)
* 네트워크
  - OSI 7계층   
  ![OSI 7계층 이미지](https://t1.daumcdn.net/thumb/R1280x0/?fname=http://t1.daumcdn.net/brunch/service/user/axm/image/yWBiLryz1rFYUXYzRVdt_Hkf6e8.jpg)
  ![OSI 7계층 이미지2](http://faq.hostway.co.kr/files/attach/images/784/434/001/679c0026b17573f5f0ba7edcafe8ad20.jpg)
  - TCP/UDP 차이점
    + 3way / 4way handshake란?   
    ![3way / 4way handshake](https://t1.daumcdn.net/thumb/R1280x0/?fname=http://t1.daumcdn.net/brunch/service/user/axm/image/E4Uz7Z-hIpzKBZ69YQcPDL6g0Lw.jpg)
* IO : 동기/비동기 & 블럭/논블럭   
![동기/비동기 and Block/Non-Block 이미지](https://i.imgur.com/oPYfrZl.png)
  - 동시성과 비동기의 차이점은??
* 리눅스 디렉터리 구조   
![리눅스 디렉터리 구조](https://raw.githubusercontent.com/lee-seul/lee-seul.github.com/master/static/img/_posts/linux_directory_structure.png)

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
