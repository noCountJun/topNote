# OOP란?
  > Object Oriented Programming
  * 객체에 집중되는 프로그래밍
  * 한번 작성한 코드를 어디서든 사용할 수 있게 하는 프로그래밍 (나의 답변)
  * 코드 재사용을 증가시키고 유지보수를 감소시키는 장점을 얻기 위해 객체들을 연결시켜서 프로그래밍 하는 것
  
  ### OOP의 4가지 특성
  
  * 캡슐화  (Encapsulation)
    * 객체 내부를 외부로부터 숨겨서 접근하지 못하게 하는것(private 은닉화)
  * 추상화  (Abstraction)
    * 공통되는 걸 묶어서 추상화 시키는것
    * ex) 이상한 나라의 앨리스에 나오는 카드들 (하트여왕, 병사들, 시민들은 앨리스가 보기에 어차피 카드들)
  * 다형성  (Polymorphism)
    * 상속받은 기능을 변경하거나 확장하는 것
      * 오버라이딩 : 부모클래스의 메서드를 재정의
      * 오버로딩 : 같은 클래스의 같은 이름의 메서드
  * 상속 (Inheritance)
    * 부모 객체의 속성을 하위 객체가 물려받는 것
  
  
# SOLID (객체 지향 설계 원칙)
  ### 1. SRP(Single Responsibility Principle) : 단일 책임 원칙   
    * 클래스는 단 하나의 책임만 가져야 하며,변경하는 이유도 하나여야 한다   
  ### 2. OCP(Open-Closed Principle) : 개방-폐쇄 원칙  
    * 확장에는 열려 있어야 하고 변경에는 닫혀 있어야 한다.
  ### 3. LSP(Liskov Substitution Principle) : 리스코프 치환 원칙
    * 상위 타입의 객체를 하위 타입의 객체로 치환해도 상위 타입을 사용하는 프로그램은 정상적으로 동작해야 한다.
  ### 4. ISP(Interface Segregation Principle) : 인터페이스 분리 원칙
    * 인터페이스는 그 인터페이스를 사용하는 클라이언트를 기준으로 분리해야 한다.
  ### 5. DIP(Dependency Inversion Principle) : 의존 역전 원칙
    * 고수준 모듈은 저수준 모듈의 구현에 의존해서는 안된다.
