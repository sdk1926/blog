# ☕️ 자바 객체 용어 정리 

## 인스턴스 
* 클래스(class)는 객체의 속성을 정의 하고, **기능을 구현하여 만들어 놓은 코드 상태**

* 실제 클래스 기반으로 생성된 객체(인스턴스)는 각각 다른 멤버 변수 값을 가지게 됨 
    * 파이썬에서 인스턴스 생성하는걸 생각하자 

* new 키워드를 사용하여 인스턴스 생성 

## 힙메모리 
* 생성된 인스턴스는 [동적메모리](https://ko.wikipedia.org/wiki/%EB%8F%99%EC%A0%81_%EB%A9%94%EB%AA%A8%EB%A6%AC_%ED%95%A0%EB%8B%B9)(heap memory)에 할당됨 

* C나 C++언어에서는 사용한 동적 메모리를 프로그래머가 해제 시켜야 함 (free() 나 delete 이용) 
* 자바에서는 Gabage Collector가 주기적으로 사용하지 않는 메모리를 수거한다. 
* 하나의 클래스로 부터 여러개의 인스턴스가 생성되고 각각 다른 메모리 주소를 가지게 됨 
    * 파이선에서 인스턴스 객체들의 메모리 주소를 찍어보면 다 달랐던 걸 생각하자 
    
## 용어정리 

* 객체 : 객체 지향 프로그램의 대상, 생성된 인스턴스 
* 클래스 : 객체를 프로그래밍 하기 위해 코드로 정의해 놓은 상태 
* 인스턴스 : new 키워드를 사용하여 클래스를 메모리에 생성한 상태 
* 멤버 변수 : 클래스의 속성, 특성 
* 메서드 : 멤버 변수를 이용하여 클래스의 기능을 구현한 함수 
* 참조 변수 : 메모리에 생성된 인스턴스를 가리키는 변수 
* 참조 값 : 생성된 인스턴스 메모리 주소 값 