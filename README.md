# memory-game
Android Studio를 이용해 만든 카드 뒤집기 메모리게임

[디자인 계획 - Figma](https://www.figma.com/design/utdsvX9imzFGH1IEPrix0x/Memory-game?node-id=0-1&t=Qicbqv3VSATxp2CP-1)

### 필요 요소
* 카드
* 타이머
* 시작, 리셋 버튼
* 시도 횟수(초기상태: 30)
* 결과 메세지

### 설명
1. start 버튼을 누른다
2. start 버튼이 안보여지게 되고, retry 버튼이 보이게 된다
3. 60초 타이머가 시작된다
4. 한 턴에 두개의 카드를 뒤집는다
5. 만약 두 카드의 이미지가 일치하면 카드가 사라진다
6. 두 카드의 이미지가 일치하지 않으면 카드는 다시 뒤집힌다
7. 한 턴이 지날때 만다 count에 숫자가 1씩 감소한다
8. 모든 카드가 사라지면 타이머가 멈추고, 결과화면(승리) 1초동안 보여주기
9. 타이머가 끝나거나, count를 모두 소진하면, 결과화면(패배) 1초동안 보여주기
10. 결과화면이 사라지거나 retry를 누르면 타이머, count가 초기화 후, 모든 카드는 뒤집히고 재배치된 후 start 버튼이 보이게 된다
