# java-lotto-precourse

# 구현할 기능 목록
1. 로또 발행 기능
   - 1,000원 당 1장의 로또를 발행한다.
   - 로또 한장은 1~45 사이의 중복되지 않는 6개의 숫자로 구성된다.
2. 당첨 번호 생성 기능
   - 당첨 번호는 1~45 사이의 중복되지 않는 6개의 숫자로 구성된다.
3. 보너스 번호 생성 기능
   - 보너스 번호는 당첨 번호 이외의 1~45 사이의 하나의 숫자이다.
4. 번호 대조 기능
   - 로또의 번호와 당첨 번호, 보너스 번호를 대조 하여 당첨 여부를 결정한다.
5. 수익률 계산 기능
   - 구매 금액과 당첨 내역을 기반으로 총 수익률을 계산한다.
6. 입출력 기능
   - 사용자가 잘못된 값을 입력할 경우 IllegalArgumentException을 발생시키고, "[ERROR]"로 시작하는 에러 메시지를 출력 후 그 부분부터 입력을 다시 받는다.
7. 예외처리 기능
   - Exception이 아닌 IllegalArgumentException, IllegalStateException 등과 같은 명확한 유형을 처리한다.