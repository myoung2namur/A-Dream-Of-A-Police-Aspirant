# 경찰 지망생의 꿈

### A Dream Of A Police Aspirant

### 도둑잡기 게임의 파이썬 버전입니다.

실행시 기본적으로 카드 7개를 나눠줍니다.
플레이어 / 딜러 공통

턴이 시작할때 플레이어와 딜러는 카드 뭉치로부터 카드 1개를 가져옵니다.
중복 카드가 있으면, 중복 카드를 버립니다.

상대의 카드중 1개를 고르고, 만일 중복이라면, 버립니다.

상대의 턴이 시작되고, 딜러는 카드 한장을 뽑고,
플레이어의 카드중 한장을 뽑고, 중복 카드를 버립니다.

이렇게 계속 반복되다가, 승리, 혹은 패배가 결정됩니다.

승리 조건과 패배 조건은 이러합니다 :

```diff
+승리조건

+ 플레이어의 카드 덱이 모두 사라진다.
+ 딜러에게 카드가 조커 한장만 남는다.

-패배 조건

- 딜러의 카드 덱이 먼저 모두 다 사라진다.
- 플레이어의 카드가 조가 단 한장만 남는다.
```

AI 딜러와 신경전을 하시며 재미있는 카드 게임을 즐기시길 바랍니다.
