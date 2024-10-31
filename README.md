# java-lotto-precourse

# 구현할 기능 목록
- [ ] 구입 금액 입력
- [ ] 중복 되지 않는 숫자 6개 반환
- [ ] 숫자 오름차순으로 정렬
- [ ] 발행한 로또 수량 및 발행 수량 만큼의 번호 출력
- [ ] 로또 당첨 확인
- [ ] 당첨 내역 출력
- [ ] 수익률 출력

# 예외 처리
- 사용자가 잘못된 값을 입력할 경우 `IllegalArgumentException`을 발생시키고, 
"[ERROR]"로 시작하는 에러 메시지를 출력 후 그 부분부터 입력을 다시 받는다.
  - `Exception`이 아닌 `IllegalArgumentException`, `IllegalStateException` 
등과 같은 명확한 유형을 처리한다.

# 예외 상황 목록

- [ ] *로또 구입 금액 예외*
  - [ ] 로또 구입 금액에 입력을 하지 않은 경우
  - [ ] 로또 구입 금액이 숫자가 아닌 경우
  - [ ] 로또 구입 금액이 1000원 미만인 경우
  - [ ] 로또 구입 금액이 1000원으로 나누어 떨어지지 않는 경우
- [ ] *로또 당첨 번호 예외*
  - [ ] 로또 당첨 번호에 입력을 하지 않은 경우
  - [ ] 로또 당첨 번호가 숫자나 구분자(,)가 아닌 경우
  - [ ] 로또 당첨 번호가 6개가 아닌 경우
  - [ ] 로또 당첨 번호가 1에서 45 사이의 수가 아닌 경우
- [ ] *보너스 번호 예외*
  - [ ] 보너스 번호에 입력을 하지 않은 경우
  - [ ] 보너스 번호가 숫자가 아닌 경우
  - [ ] 보너스 번호가 1개가 아닌 경우
  - [ ] 보너스 번호가 1에서 45 사이의 수가 아닌 경우