# 자동차 경주 게임
## 진행 방법
* 자동차 경주 게임 요구사항을 파악한다.
* 요구사항에 대한 구현을 완료한 후 자신의 github 아이디에 해당하는 브랜치에 Pull Request(이하 PR)를 통해 코드 리뷰 요청을 한다.
* 코드 리뷰 피드백에 대한 개선 작업을 하고 다시 PUSH한다.
* 모든 피드백을 완료하면 다음 단계를 도전하고 앞의 과정을 반복한다.

## 온라인 코드 리뷰 과정
* [텍스트와 이미지로 살펴보는 온라인 코드 리뷰 과정](https://github.com/next-step/nextstep-docs/tree/master/codereview)

## ToDo
* [x]  빈 문자열 또는 null 값을 입력할 경우 0을 반환해야 한다.
* [x]  숫자 하나를 문자열로 입력할 경우 해당 숫자를 반환한다.
* [x]  숫자 두개를 컴마(,) 구분자로 입력할 경우 두 숫자의 합을 반환한다.
* [x]  구분자를 컴마(,) 이외에 콜론(:)을 사용할 수 있다.
* [x]  “//”와 “\n” 문자 사이에 커스텀 구분자를 지정할 수 있다. 
* [x]  음수를 전달할 경우 RuntimeException 예외가 발생해야 한다.

## feedback ToDo
* [x]  메소드명 표현 다시 살핀다.
* [x]  객체지향 생활 체조 원칙 규칙 적용한다. 1: 한 메서드에 오직 한 단계의 들여쓰기(indent)만 한다.
* [x]  Pattern static final 로 상수로 사용한다.(=캐싱 높은 cost문제 해결.)
* [x]  구분자 의미전달을 위해 상수로 선언한다.
* [x]  0 과 같은 숫자 해당 값이 나타내는 의미를 상수로 표현한다.
* [x]  NullAndEmptySource 학습 후 test code 적용한다.
* [x]  아래와 같이 2가지 기능이 StringAddCalculator 에 존재. 1번을 클래스로 떼어내보자.
    * 1.문자열을 구분자를 기준으로 분리하여 숫자 배열로 변경한다. 
    * 2.모든 수 더하기. 
