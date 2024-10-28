# java-racingcar-precourse 3:20 - 3:47
## 기능 요구사항 이해
1. 차량 n대의 이름을 쉼표(,)기준으로 입력받는다.
1-1. 이름은 5자 이하.
2. 몇 번(k번) 이동 할 것인지 입력받는다
3. 이동할 떄마다 난수(0~9)에 따라 전진 여부가 결정된다.
3-1. 전진 조건 : 난수 4 이상
4. 각 이동마다 이름과 총 전진량을 출력한다.
5. 총 전진량에 따라 우승자를 출력한다
5-1. 우승자가 여러 명일 경우 쉼표(,)를 기준으로 출력한다.

## 예외상황
### 이름
1. 이름이 5글자 초과 -> 양쪽 공백은 제거하고 나서 유효성 검사
2. 이름 중복 제거
### 횟수 입력
1. 음수 및 숫자가 아닌 것 예외

##### arraylist로 사용 할 것 