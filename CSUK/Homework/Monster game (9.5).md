# Instructions:
Monster game (9.5)
The aim of this text based game is to open as many doors as possible without meeting the monster.
At the start of the game, the user is facing three doors.
They have to decide which door they will use to escape the room they are in.
If they do not meet the monster the game carries on with another three doors.
Each time the user manages to escape a room without meeting the monster they score one point.
The game ends when the user meets the monster.

# Answer:
```
import random
score = 0
userDoor = 0
monsterDoor = 1
def doors():
  print ('''
_____1_____    _____2____   _____3_____
|  __  __  |  |  __  __  |  |  __  __  |
| |  ||  | |  | |  ||  | |  | |  ||  | |
| |  ||  | |  | |  ||  | |  | |  ||  | |
| |__||__| |  | |__||__| |  | |__||__| |
|  __  __()|  |  __  __()|  |  __  __()|
| |  ||  | |  | |  ||  | |  | |  ||  | |
| |  ||  | |  | |  ||  | |  | |  ||  | |
| |  ||  | |  | |  ||  | |  | |  ||  | |
| |  ||  | |  | |  ||  | |  | |  ||  | |
| |__||__| |  | |__||__| |  | |__||__| |
|__________|  |__________|  |__________|''')

def monster():
    print ('''
        .-""-"-""-.
       | .--.-.--. |
       |` >       `|
       | <         |
       (__..---..__)
      (`|o_/ _o/|`)
       (    >    )/
     [>=|   vvv   |=<]
        __   /__/
            '-'
 ''')
print ('Halloween Game')

print ('Avoid the monster!')
while userDoor != monsterDoor:
    monsterDoor = random.randint(1, 3)
    print ('Three doors ahead...')
    doors()
    print ('Is the Monster behind door..')
    userDoor = int(input ('1,2, or 3?'))
    if userDoor ==  monsterDoor:
        print (' ARGHHH! MONSTER')
        monster()
    else:
        print('Phew! No Monster!')
        print('You enter the next room. ')
        score += 1
        print("Your current score is " + str(score))

```
