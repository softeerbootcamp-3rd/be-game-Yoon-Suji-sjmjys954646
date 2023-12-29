# 블랙잭 게임 구현
## 게임 룰
### 게임 시작 전
1. 유저와 딜러(컴퓨터) 두 명이 블랙잭 게임 진행 - 유저는 100원을 가지고 시작
2. 게임 시작 전에 유저가 원하는 만큼 돈을 베팅
   
### 게임 진행
1. 유저와 딜러가 랜덤으로 두 장의 카드를 받음
2. 유저의 카드는 모두 공개되고, 딜러의 카드는 한 장만 공개
3. 현재 딜러가 갖고 있는 카드의 합이 17 이상이면 더 이상 카드를 받지 않는다.
   
    3-1. 딜러가 카드를 받았을 때, 합이 22이상이 되면 유저가 승리한다. 
  
4. 유저는 카드를 받을지 안 받을지 선택할 수 있다.

    4-1. 유저가 카드를 받았을 때, 합이 22이상이 되면 딜러가 승리한다.
  
5. 딜러와 유저 둘 다 카드를 받고 싶지 않은 경우, 게임이 종료되고 패를 공개한다.
6. 딜러와 유저 중 카드의 합이 21에 더 가까운 사람이 승리한다.

    6-1. 유저가 승리하면 베팅한 만큼의 돈을 더 받는다. 블랙잭으로 승리시(카드의 합이 정확히 21인 경우) 유저는 베팅한 것의 1.5배의 돈을 받는다.
  
    6-2. 딜러와 비기거나 딜러가 승리하면 베팅한 만큼의 돈을 잃는다.
  
### 게임 종료
유저가 더 이상 베팅할 돈이 없거나, 더 게임을 진행할 의사가 없을 경우 게임을 종료한다.

## TODO
유저의 기록을 저장하는 기능
