# PB2-py-akmens_skeres_papiritis
akmens skeres papirs



### programe code
```python
import random

while True:

    for i in range((random.randrange(0, 4))):
        computer = i
        if computer == 1:
            player = int(input('akmens (1), papirs(2) vai skeres(3)'))
            print('akmens')
            if computer == player:
                print('draw')
            if computer == 1 and player == 3:
                print('computer win')
            if computer == 2 and player == 1:
                print('computer win')
            if computer == 3 and player == 2:
                print('computer win')
            if computer == 3 and player == 1:
                print('player win')
            if computer == 1 and player == 2:
                print('player win')
            if computer == 2 and player == 3:
                print('player win')

        if computer == 2:
            player = int(input('akmens (1), papirs(2) vai skeres(3)'))
            print('papirs')
            if computer == player:
                print('draw')
            if computer == 1 and player == 3:
                print('computer win')
            if computer == 2 and player == 1:
                print('computer win')
            if computer == 3 and player == 2:
                print('computer win')
            if computer == 3 and player == 1:
                print('player win')
            if computer == 1 and player == 2:
                print('player win')
            if computer == 2 and player == 3:
                print('player win')
        if computer == 3:
            player = int(input('akmens (1), papirs(2) vai skeres(3)'))
            print('skeres')
            if computer == player:
                print('draw')
            if computer == 1 and player == 3:
                print('computer win')
            if computer == 2 and player == 1:
                print('computer win')
            if computer == 3 and player == 2:
                print('computer win')
            if computer == 3 and player == 1:
                print('player win')
            if computer == 1 and player == 2:
                print('player win')
            if computer == 2 and player == 3:
                print('player win')
```

### Tabula

computer's move |  player's move |  results 
-------------|--------------|----------------
akmens | papirs | player wins
skeres |akmens|player wins
papirs | skeres| player wins
akmens|akmens|draw
papirs | papirs |draw
skeres|skeres|draw
akmens | skeres|computer wins
papirs|akmens|computer wins
skeres | papirs |computer wins