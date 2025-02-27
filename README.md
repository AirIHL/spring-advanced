# SPRING ADVANCED



## SPRING 심화 주차 개인 과제


필수 기능 완료하였습니다.
Validation을 통해 비밀번호 제약 사항을 Service에서가 아닌 DTO에서 구현하면서 정규표현식에 대해 더 자세히 알게 되는 기회가 되었습니다.
또한 N + 1 문제를 통해 JPQL fetch join이 아닌 @EntityGraph 기반의 구현을 해보며 EntityGraph에 대해 자세히 알게 되었습니다.
테스트 코드 연습도 진행하면서 조금 더 테스트 코드에 친숙해 진 것 같습니다.


API로깅을 Interceptor를 활용하여 진행하고 있었습니다. 하지만 미완성이고 이해도가 아직 높지 않아 더 공부를 한뒤 주말에 마저 구현해보려고 합니다.
처음에 Intercept와 AOP 중 하나를 활용하여 로깅을 구현하라고 적혀 있어 Intercept와 AOP를 찾아보며 개념에 대해서는 더 잘알게 된 것 같습니다.
찾아 보면서 AOP는 특정 메서드 단위에서 로깅을 하기에 좋다고 하는데 그러면 이번 과제에서는 AOP로 구현하는게 더 좋은 건가요?



### Lv.1

1. src/main/java/org/example/expert/domain/auth/service/AuthService.java
2. src/main/java/org/example/expert/client/WeatherClient.java
3. src/main/java/org/example/expert/domain/user/dto/request/UserChangePasswordRequest.java
   src/main/java/org/example/expert/domain/user/service/UserService.java


### Lv.2

src/main/java/org/example/expert/domain/todo/repository/TodoRepository.java


### Lv.3

  1-1. src/test/java/org/example/expert/config/PasswordEncoderTest.java
  
  2-1. src/test/java/org/example/expert/domain/manager/service/ManagerServiceTest.java
  
  2-2. src/test/java/org/example/expert/domain/comment/service/CommentServiceTest.java
  
  2-3. src/main/java/org/example/expert/domain/manager/service/ManagerService.java
