# signup_project

A new Flutter project.

## 25 스트림과 파이어베이스 
- 지속적으로 데이터를 받을 때 사용 

            즉시 사용가능       기다려야 사용가능
단일 데이터     int                Future<int>
복수 데이터    List<int>           Stream<int>

이 Stream을 구독하고 있는 한 스트림에 데이터가 전달될 때 마다 그 즉시 알 수 있다.

## 26 파이어베이스 롤 
- 