# memory-game
Android Studio를 이용해 만든 카드 뒤집기 메모리게임

### 필요 요소
* 카드
* 타이머
* 시작, 리셋 버튼
* 시도 횟수
* 결과 메세지

### 설명
1. start 버튼을 누른다
2. start 버튼이 안보여지게 되고, retry 버튼이 보이게 된다
3. 60초 타이머가 시작된다
4. 한 턴에 두개의 카드를 뒤집는다
5. 만약 두 카드의 이미지가 일치하면 카드가 사라진다
6. 두 카드의 이미지가 일치하지 않으면 카드는 다시 뒤집힌다
7. 한 턴이 지날때 만다 count에 숫자가 1씩 추가된다
8. 모든 카드가 사라지면 타이머가 멈추고, 성공 메세지가 뜬다
9. 타이머가 끝나면 실패 메세지가 뜬다
10. retry를 누르면 타이머, count가 초기화 되고, 모든 카드는 뒤집히고 재배치된 후 start 버튼이 보이게 된다
