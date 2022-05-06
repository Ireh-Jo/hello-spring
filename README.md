## 빌드하고 실행하는 방법
1. 명령 프롬프트(cmd) 실행
2. 프로젝트 경로로 이동
3. gradlew.bat clean build
4. cd build/libs
5. java -jar hello-spring-0.0.1-SNAPSHOT.jar

## 스프링 웹 개발 기초
- 정적 컨텐츠
- MVC와 템플릿 엔진
- API

## 스프링 빈을 등록하는 2가지 방법
- 컴포넌트 스캔과 자동 의존관계 설정
- 자바 코드로 직접 스프링 빈 등록

DI에는 필드 주입, setter 주입, 생성자 주입 이렇게 3가지 방법이 있다. 의존관계가 실행중에
동적으로 변하는 경우는 거의 없으므로 생성자 주입을 권장한다.

## 스프링의 장점
- 개방-폐쇄 원칙(OCP, Open-Closed Principle)
  - 확장에는 열려있고, 수정, 변경에는 닫혀있다.
- 스프링의 DI (Dependencies Injection)을 사용하면 기존 코드를 전혀 손대지 않고, 설정만으로 구현 클래스를 변경할 수 있다.