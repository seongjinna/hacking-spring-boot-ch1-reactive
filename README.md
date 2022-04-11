# hacking-spring-boot-ch1-reactive
스프링 부트 웹 애플리케이션 만들기

## Getting Started
- Java version : JDK 8
- Spring Boot : 2.4.2

### Dependencies
- Spring Reactive Web : 스프링 웹플럭스 + 내장형 네티
- Thymeleaf : 템플릿 엔진

### Test
- curl -N -v localhost:8080/server
- curl -N -v localhost:8080/served-dishes
- http://localhost:8080

### Lessons learned
- 레스토랑 서빙 점원이 손님 및 주방과 어떻게 의사소통하는지 살펴보면서 리액티브 프로그래밍의 기초를 살펴봤다.
- 리액티브 프로그래밍 개념을 스프링 웹플럭스 컨트롤러와 서비스에 적용해봤다.
- 첫 번째 스프링 부트 애플리케이션을 실행하고 cURL을 사용해서 비동기 스트림으로 제공되는 요리가 사용되는 모습을 살펴봤다.
- 첫 번째 타임리프 템플릿을 만들고 정적인 웹 페이지로 렌더링해서 화면에 표시했다.