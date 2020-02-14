* [한재엽기술면접자료](https://github.com/JaeYeopHan/Interview_Question_for_Beginner#%EB%A9%B4%EC%A0%91%EC%97%90%EC%84%9C-%EB%B0%9B%EC%95%98%EB%8D%98-%EC%A7%88%EB%AC%B8%EB%93%A4)
* [김대희기술면접자료](https://github.com/DaeHeeKim93/DaeHeeKim-Review)
* [WeareSoft 기술면접자료](https://github.com/WeareSoft/tech-interview)
* [jobhope기술면접자료](https://github.com/jobhope/TechnicalNote)
* [정아마추어면접답](https://jeong-pro.tistory.com/category/%EC%8B%A0%EC%9E%85%20%EA%B0%9C%EB%B0%9C%EC%9E%90%20%EB%A9%B4%EC%A0%91%20%EA%B8%B0%EC%B4%88)
 
JAVA, 객체지향

- OOP? SOLID?
- JVM구조,GC동작원리
- 접근제어자
- 어노테이션
  주석과는 역할이 다르지만 코드에 달아 클래스의 특별한 의미를 부여하거나 기능을 주입할 수 있다
- Interface / abstract의 차이
- StringBuilder / StringBuffer의 차이
- try-with-resources
- Synchronize란?
- Synchrozize를 하기 위한 방법은?
- Serialize란
- Serialize와 json의 상관관계
- Serialize로 통신할 때 문제점
- static에 대해
- 제네릭이란?
  타입의 안정성을 보장
  메서드나 컬렉션 클래스에서 사용하고 
  컴파일시에 객체의 타입을 체크하기 때문에 객체의 타입안정성을 높이고 형변환의 번거로움을 줄여준다
  그래서 코드도 더 간결해짐
- 대표적인 제네릭 메서드는? 
- Collections.sort()
- 오버로딩, 오버라이딩
  오버로딩
  - 같은 이름 같은 return, 다른 매개변수
  오버라이딩
  - 상위클래스의 메서드를 하위클래스에서  재정의
- CheckedException / UnCheckedException 차이
- final / finally / finalize 차이
  final 다른곳에서 못건드린다
  finally 
  - try-catch 나 try-catch-resource 구문을 사용할때 마무리 해줘야 하는 작업이 있을때 사용하는 코드블록
  finalize() 
  - gc에서 호출되는 함수로 절대 호출하면 안되는 함수
- 람다식 단점
  - 남발하면 코드가 지저분해진다
- call by value와 call by reference의 차이
  

자료구조

- 컬렉션프레임워크에 대해 설명
  List, Map, Set, Stack, Queue 인터페이스를 기준으로 여러 구현체가 존재
  여러가지 데이터를 다루는데 있어서 표준화된 클래스를 제공해주기 때문에 편하게 사용 가능하다
- Stack, Queue, LinkedList, Binary Search 
- Stack / LinkedList / List / vector의 차이
- HashMap / HashTable / ConcurrentHashMap의 차이

업무

- MVC패턴에 대해 설명
  Model, View, Controller
  1. Controller
     - 클라이언트에게 요청을 받았을때 모델에게 전달하기 쉽게 가공해서 모델에게 전달하고 모델이 업무를 마치면 결과를 view에 전달
  2. Model
     - 비즈니스 로직을 구현하는 영역, DB 연결해서 crud작업
  3. View
     - 컨트롤러한테 받은 모델값을 가지고 화면에 출력

- UI와 UX의 차이
- XSS(Cross*site scripting) 이란
- 웹 접근성이란
- 64bit / 32bit 차이
- 검색이 어떤 방식으로 작동하는가
- 쓰레드풀에 대해 설명하라, 왜 쓰는지, 무엇인지
- url에 www.naver.com 입력하면 화면에 나타나기까지의 과정
- 위과정에서 만약 인터넷이 끊기면 어디까지 진행되는가
- 해시함수 sha*1에대해 설명
- DAO DTO에 대해 설명
- 디자인패턴 설명
- 자바와 자바스크립트의 차이
- 컴파일러 / 인터프리터 차이
- HashTable의 출동해결 방법
- 대칭키/ 비대칭키 암호화 차이

 

- 스프링 프레임워크의 특징
- 스프링 IoC 란
- Di란
- POJO란
- OOP와 AOP 의 차이
- Spring boot 설정 자동화 원리
  @EnableAutoConfiguration

네트워크

- OSI 7계층이란
- TCP / IP 에 대해 설명
- TCP / UDP의 차이
  1. UDP (User Datagram Protocol, 사용자 데이터그램 프로토콜)
     - 비연결형 프로토콜
  2. TCP ( Transmission Control Protocol, 전송제어 프로토콜)
     - 신뢰성 있는 바이트 스트림을 전송
- HTTP / TCP 차이
- HTTP / HTTPS 차이 
  - HTTP는 보안에 취약하다 
  - SSL(Secure Socket Layer) 또는 TLS(Transport Layer Security) 라는 프로토콜을 조합해서 HTTP 통신내용을 암호화 할수있다
  - HTTPS 에서 HTTP는 SSL과 통신하고, SSL 이 TCP와 통신하게 된다.
  - SSL을 사용한 HTTPS는 암호와와 증명서, 안전성 보호를 이용할 수 있다
  - 모든 웹페이지에서 HTTPS를 사용하지 않는 이유는 
    - 평문통신에 비해 암호화 통신이 CPU나 메모리 등 리소스가 많이 필요해서 민감한 정보를 다룰때만 HTTPS에 의한 암호화 통신을 사용한다.
- HTTPS 에서 S는 어느 계층에 속하나
- 쿠키 , 세션
- 샤딩이란
- get / post /crud 에 대해 설명
- HTTP Method에 대해 설명
- Connection Timeout / Read Timeout의 차이
- RESTful API
  - REST / SOAP 에 대해 설명
  - RESTFul 하다(하지 않다) 의 의미
    Representational State Transfer의 약자
    여기에 ~ful 이라는 형용사 어미를 붙여 ~한 API라는 표현을 사용
    즉 Rest의 기본원칙을 성실히 지킨 서비스가  RestFul하다 할 수 있다
    1. 리소스와 행위를 명시적이고 직관적으로 분리
    - 리소스는 URI로 표현되고 명사로 표현되야 한다.
    - 행위는 HTTP Method 
      - GET(조회), POST(생성), PUT(]전체 수정), PATCH(일부수정), DELETE를 분명한 목적으로 사용
    1. Header와 Body를 명확하게 분리
       - Body : Entity에 대한 내용
       - Header :  API 버전정보나 응답받고자 하는 타입등
    2. URI 가 플랫폼 중립적
       - 브라우저에서 form-data로 보내고, 서버에서는 json으로 보내기 보다는 하나로 통일시켜야 한다
  - 장단점
    장점
    - open API를 제공하기 쉽다
    - 원하는 타입으로 데이터를 주고 받을 수 있따
    단점
    - HTTP 통신모델에서만 지원한다.

DB

- 디비 풀은 왜쓰는가
- join 방식
- RDBMS / NoSQL의 차이
- SQL Injection이란?
- 몽고DB의 특성
- NoSQL
  관계형 데이터 모델을 지양하며, 스키마가 없거나 느슨한 스키마를 제공하는 저장소
  조인이 없고 RDBMS보다 융통성있는 데이터 모델을 사용
  ex) MongoDB, HBase, Cassandra
- 정규화
  - RDB에서 중복을 최소화하기위해 데이터를 구조화 하는것 
  - 정규화때문에 조인이 많아져서 성능저하가 일어날 결우 반정규화 한다
- 트랜잭션 (ACID)
  작업의 완전성을 보장해 주는것 
  1. 원자성 (Atomicity)
     - 중간에 문제가 발생되면 다 롤백되야 한다. 
  2. 일관성 (Consistency)
     - 완료된 다음에도 일어나기 전의 상황과 동일하게 일관성을 보장
  3. 고립성 (Isolation)
     - 각각의 트랜잭션은 서로 간섭없이 독립적으로 수행되야 함
  4. 지속성 (Durability)
     - 정상종료된 후 영구적으로 DB에 저장되야 함

운영체제

- 데드락이란?
  - 데드락 4대요소
- 멀티 쓰레드 환경에서 주의사항

스크립트

- 클로저란
- 변수스코프체인인란

기타

- 각 프로젝트 별로 기술적으로 가장 어려웠던 점과 극복했던 방법
- 이전 프로젝트에서 어떤 갈등이 있었고, 어떻게 해결하였나
- 이 직무를 위해 당신이 정말 열심히 했다고 생각하는 것은?

알고리즘 및 팁

- 자유 알고리즘 시간복잡도 Big O는 다 외워라
- 문자열 조작 (뒤집기, 조합, 잘라내기)
- Stack, Queue, LinkedList, Binary Search 응용
- 깊이우선탐색, 너비우선탐색
- 1부터 100까지 더하는 프로그램
- 소팅 알고리즘을 슈도 코드로 구현하되, 변수를 사용하지 않고 해봐라
- 정렬 알고리즘 중 가장 빠른방식은 무엇인가, 그 알고리즘에 대해 설명해봐라
- 자바로 자판기를 설계할 때 어떻게 설계할 것인가.
  - 깊이우선탐색, 너비우선탐색






