# javascript-lotto-precourse

## 구현한 기능 목록

- [x]  사용자로부터 로또 구입 금액을 입력 받는다.
    - [x]  입력받은 금액의 유효성 검사를 실시한다.
- [x]  발행한 로또 수량 및 오름차순으로 정렬된 로또 번호를 출력한다.
- [x]  쉼표(,)를 기준으로 당첨 번호를 구분해서 입력 받는다.
    - [x]  입력받은 당첨 번호의 유효성 검사를 실시한다.
- [x]  사용자로부터 보너스 번호를 입력 받는다.
    - [x]  보너스 번호의 유효성 검사를 실시한다.
- [x]  Lotto class 분리 및 리팩토링
- [ ]  당첨 내역 계산
- [ ]  당첨 통계 내역을 출력한다.
- [ ]  총 수익률을 소수점 둘째 자리에서 반올림해서 보여준다.
- [ ]  리팩토링

## 예외 처리 사항

구입 금액

- 값을 입력해야 한다.
- 양수여야 한다.
- 1000원으로 나누어 떨어져야 한다.
- 한 개의 숫자만 입력해야 한다.

당첨 번호

- 값을 입력해야 한다.
- 구분된 값은 1~45 사이의 숫자이다.
- 값은 중복되면 안된다.
- 쉼표를 구분자로 입력해야 한다.
- 6개의 숫자를 입력해야 한다.

보너스 번호

- 값을 입력해야 한다.
- 1~45 사이의 숫자여야 한다.
- 당첨 번호의 숫자와 중복되면 안된다.
- 한 개의 숫자만 입력해야 한다.