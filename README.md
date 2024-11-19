# 우아한테크코스 활동 기록 📝

우아한테크코스 6기 백엔드 활동 기록입니다 😊 주요 기술 스택은 **Java 17, Springboot 3, MySQL**(및 H2)입니다. 교육 과정 외에도 추가로 관심 있는 주제를 탐구하며 [블로그](https://velog.io/@jongmee/posts)를 운영해왔습니다.

<br>

## 🌱 레벨1 - 단위테스트, 클린코드, OOP, DB

> 2024.02.13 ~ 2024.04.05

### 나의 학습 목표
- Java 라이브러리 기능의 목적과 **객체 지향 설계**를 학습하고 실제 코드에 적용하는 사이클에 집중한다.
- 단순히 사용법을 익히는 것을 넘어, **동작 원리**와 **사용 목적**을 명확히 이해하고 이를 **응용하고 판단하는 능력**을 기른다.
- **읽기 좋은 코드**를 고민하고 **단위 테스트**와 **리팩토링**을 반복하며 신뢰도 있는 코드를 작성한다.

### 미션 목록

#### 🚘 자동차 경주
> [1단계 PR 주소](https://github.com/woowacourse/java-racingcar/pull/663) <br> [2단계 PR 주소](https://github.com/woowacourse/java-racingcar/pull/795)
- 도메인 모델별로 책임을 고민하며 도서 이펙티브 자바와 함께 OOP를 공부했습니다.

#### 🪜 사다리 타기
> [1단계 PR 주소](https://github.com/woowacourse/java-ladder/pull/279) <br> [2단계 PR 주소](https://github.com/woowacourse/java-ladder/pull/352)
- 신뢰도 높은 도메인 모델 객체를 만드며 도메인 설계 경험을 쌓았습니다.

#### ♣️ 블랙잭
> [1단계 PR 주소](https://github.com/woowacourse/java-blackjack/pull/621) <br> [2단계 PR 주소](https://github.com/woowacourse/java-blackjack/pull/705)
- 생성자 주입, 조합을 사용해 의존성 최소화를 목표로 도메인 객체를 설계하고 Value Object와 불변 객체를 학습하고 미션에 도입했습니다.

#### ♟️ 체스 게임
> [1,2단계 PR 주소](https://github.com/woowacourse/java-chess/pull/718) <br> [3단계 PR 주소](https://github.com/woowacourse/java-chess/pull/736) <br> [4단계 PR 주소](https://github.com/woowacourse/java-chess/pull/778)
- MVC 패턴의 컨트롤러 계층에서 체스 게임의 상태에 따라 게임을 전개하도록 상태 패턴을 도입했습니다.
- 함수형 프로그래밍을 학습하고 Java의 함수형 프로그래밍 관련 기능을 활용해 의도가 명확히 전달되는 코드를 작성하고자 했습니다.
- 제네릭, 함수형 인터페이스를 활용해 MySQL Connection과 SQL을 관리했습니다.

### 블로그 게시글 목록

| 제목 | 태그 |
| :- | :- |
| [[JAVA] 메서드 간 공통 로직을 함수형 인터페이스를 사용해서 분리하자](https://velog.io/@jongmee/JAVA-%EB%A9%94%EC%84%9C%EB%93%9C-%EA%B0%84-%EA%B3%B5%ED%86%B5-%EB%A1%9C%EC%A7%81%EC%9D%84-%ED%95%A8%EC%88%98%ED%98%95-%EC%9D%B8%ED%84%B0%ED%8E%98%EC%9D%B4%EC%8A%A4%EB%A5%BC-%EC%82%AC%EC%9A%A9%ED%95%B4%EC%84%9C-%EB%B6%84%EB%A6%AC%ED%95%98%EC%9E%90) | `람다식` `함수형 인터페이스` `제네릭` |
| [[JAVA] 불변 객체](https://velog.io/@jongmee/JAVA-%EB%B6%88%EB%B3%80-%EA%B0%9D%EC%B2%B4) | `불변 객체` |
| [[JAVA] static object는 GC의 대상이 아니다?](https://velog.io/@jongmee/JAVA-static-object%EB%8A%94-GC%EC%9D%98-%EB%8C%80%EC%83%81%EC%9D%B4-%EC%95%84%EB%8B%88%EB%8B%A4) | `JVM` `Heap Memory` |
| [[JAVA] 자바는 어떤 정렬 알고리즘을 사용할까?](https://velog.io/@jongmee/JAVA-%EC%9E%90%EB%B0%94%EB%8A%94-%EC%96%B4%EB%96%A4-%EC%A0%95%EB%A0%AC-%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98%EC%9D%84-%EC%82%AC%EC%9A%A9%ED%95%A0%EA%B9%8C) | `Sorting Algorithm` |
| [[JAVA] Thread와 Thread Scheduling](https://velog.io/@jongmee/JAVA-Thread%EC%99%80-Thread-Scheduling) | `Thread` `Thread Scheduling` |
| [[회고] 우테코 백엔드 6기 Level 1 🎉](https://velog.io/@jongmee/%ED%9A%8C%EA%B3%A0-%EC%9A%B0%ED%85%8C%EC%BD%94-%EB%B0%B1%EC%97%94%EB%93%9C-6%EA%B8%B0-Level-1) | `회고` |

### 발표
[[10분 테코톡] 미아의 Java Collection Framework](https://www.youtube.com/watch?v=FrPCDEiindY)

<br>

## 🌿 레벨2 - Springboot, JDBC, JPA, MySQL, External API
> 2024.04.16 ~ 2024.06.14

### 나의 학습 목표

- 웹 애플리케이션을 개발하며 새로운 기술을 익힐 수 있는 나만의 학습 방법을 찾는다.
- 레거시 코드를 리팩토링하고 새 기능을 도입하는 경험을 쌓으며 하나의 애플리케이션을 완성한다. <br>
  (이전 미션의 코드를 가져와 다음 미션을 진행하는 방식에서 모든 미션에서 페어와 협의 끝에 제 코드가 선택되었습니다.)

### 미션 기록

#### ✅ 방탈출 예약 관리: Springboot, JDBC, H2
> [1~3단계 PR 주소](https://github.com/woowacourse/spring-roomescape-admin/pull/4) <br> [4~9단계 PR 주소](https://github.com/woowacourse/spring-roomescape-admin/pull/95)

- 프로그램의 모든 계층에 대한 슬라이싱 테스트와 E2E 테스트를 하며 Spring Web MVC를 학습했습니다.

#### ✅ 방탈출 사용자 예약: Springboot, JDBC, H2
> [1~3단계 PR 주소](https://github.com/woowacourse/spring-roomescape-member/pull/21) <br> [4~6단계 PR 주소](https://github.com/woowacourse/spring-roomescape-member/pull/92)

- 서비스 정책이 구체화되면서 유효성 검증의 위치과 예외 처리에 집중했습니다.
- 요구사항 외에도 예약 도메인에서 트랜잭션 개념이 중요하다고 판단하여 스프링의 트랜잭션을 학습하고 코드에 적용했습니다. 

#### ✅ 방탈출 예약 대기: Springboot, JPA, MySQL
> [1~2단계 PR 주소](https://github.com/woowacourse/spring-roomescape-waiting/pull/1) <br> [3~4단계 PR 주소](https://github.com/woowacourse/spring-roomescape-waiting/pull/120)

- 프로그램에 JPA 도입하면서 id 채번 전략, global fetch 전략을 학습하고 코드에 적용했습니다.
- 효율적인 쿼리를 통해 JPA 영속성 컨텍스트의 캐시와 데이터베이스 리소스를 절약하고자 했습니다.
- 자체적으로 MySQL을 미션에 도입해서 예약 생성 API를 동시성을 고려하여 구현했습니다.

#### ✅ 방탈출 결제 / 배포: Springboot, JPA, MySQL
> [1단계 PR 주소](https://github.com/woowacourse/spring-roomescape-payment/pull/14) <br> [2~4단계 PR 주소](https://github.com/woowacourse/spring-roomescape-payment/pull/98) <br> [추가 단계: 비동기 메소드 예외 처리](https://github.com/jongmee/spring-roomescape-payment/tree/step2-2)

- PG사의 API에 결제 요청, 결제 내역 저장, 방탈출 예약 생성을 하나의 논리적 트랜잭션으로 구현했습니다.
- 이 때 TransactionalEventListener를 활용해서 롤백 처리 로직과 기존 로직을 분리하고 예약 도메인과 결제 도메인의 의존도를 낮추었습니다.
- 또한 비동기 메소드로 외부 API를 호출하여 외부 API가 방탈출 어플리케이션의 데이터베이스 connection을 점유하지 않도록 했습니다.

### 블로그 게시글 목록

| 제목 | 태그 |
| :- | :- |
| [[Springboot] Spring Web MVC와 Web layer 테스트](https://velog.io/@jongmee/Springboot-Spring-MVC%EC%99%80-%ED%85%8C%EC%8A%A4%ED%8A%B8) | `Spring MVC` `org.springframework.test` |
| [[Springboot] @DirtiesContext는 H2 DB를 초기화해줄까?](https://velog.io/@jongmee/DirtiesContext%EB%8A%94-H2-DB%EB%A5%BC-%EC%B4%88%EA%B8%B0%ED%99%94%ED%95%B4%EC%A4%84%EA%B9%8C) | `H2`, `org.springframework.test` |
| [[Springboot] 유효성 검증과 예외 처리](https://velog.io/@jongmee/Springboot-%EC%9C%A0%ED%9A%A8%EC%84%B1-%EA%B2%80%EC%A6%9D%EA%B3%BC-%EC%98%88%EC%99%B8-%EC%B2%98%EB%A6%AC) | `ExceptionHandler` `Validation` |
| [[Database] MySQL InnoDB의 Read-Only Transaction 최적화](https://velog.io/@jongmee/Database-InnoDB%EC%9D%98-Read-Only-Transaction-%EC%B5%9C%EC%A0%81%ED%99%94) | `MySQL` `Transaction` |
| [[Springboot] JDBC와 함께 @Transactional 알고 써보기](https://velog.io/@jongmee/Springboot-JDBC%EC%99%80-%ED%95%A8%EA%BB%98-Transactional-%EC%95%8C%EA%B3%A0-%EC%8D%A8%EB%B3%B4%EA%B8%B0) | `JDBC` `Transaction` |
| [[Springboot] Json 문자열을 Enum 값으로 변환/검증하기](https://velog.io/@jongmee/Springboot-Json-%EB%AC%B8%EC%9E%90%EC%97%B4%EC%9D%84-Enum-%EA%B0%92%EC%9C%BC%EB%A1%9C-%EB%B3%80%ED%99%98%EA%B2%80%EC%A6%9D%ED%95%98%EA%B8%B0) | `DTO` `Enum` `Validation` |
| [[트러블슈팅] 예약 생성 API에서 동시성 고려하기](https://velog.io/@jongmee/%ED%8A%B8%EB%9F%AC%EB%B8%94%EC%8A%88%ED%8C%85-%EC%98%88%EC%95%BD-%EC%83%9D%EC%84%B1-API%EC%97%90%EC%84%9C-%EB%8F%99%EC%8B%9C%EC%84%B1-%EA%B3%A0%EB%A0%A4%ED%95%98%EA%B8%B0) | `Concurrency` `Lock` `MySQL` `JPA` |
| [[트러블슈팅] 이벤트와 비동기 메소드로 외부 api 호출 롤백하기 (그리고 테스트하기)](https://velog.io/@jongmee/%ED%8A%B8%EB%9F%AC%EB%B8%94%EC%8A%88%ED%8C%85-%EC%9D%B4%EB%B2%A4%ED%8A%B8%EC%99%80-%EB%B9%84%EB%8F%99%EA%B8%B0-%EB%A9%94%EC%86%8C%EB%93%9C%EB%A1%9C-%EC%99%B8%EB%B6%80-api-%ED%98%B8%EC%B6%9C-%EB%A1%A4%EB%B0%B1%ED%95%98%EA%B8%B0-%EA%B7%B8%EB%A6%AC%EA%B3%A0-%ED%85%8C%EC%8A%A4%ED%8A%B8%ED%95%98%EA%B8%B0) | `Spring Application Event` `Transaction` |

<br>
                                            
