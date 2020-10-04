# Arduino-UNO-Chrome-Game

Chrome Dinosaur Game ported on Arduino.

## Project Resources

### Hardware:

1. Arduino UNO R3
2. 16x2 LCD Keypad Shield

### Software:

1. [Arduino](https://www.arduino.cc/en/Main/Software)

## Game Features

1. Game speeds up the longer you play it.
2. The cactuses are initialy seperated by minimaly 5 spaces, as the game progresses it goes down to 3.
3. The dinosaur is in the air 3 loop cycles after it jumps.

After you loose, press the select button to restart the game.

## Technical Stats

1. There is 500ns interrupt pooling to check if the Up button is pressed and thus there are no issues with delay blocking the input.
2. Cheating by holding the Up button constantly or spaming it are prevented.
3. The dinosaur is in the air 3 loop cycles after it jumps.

## Images

#### 1. In-Game Screen

![In-Game Screen](https://raw.githubusercontent.com/cmulay/Arduino-Dinosaur-Game/master/img/img2jpg)

#### 2. Game Over Screen

![Game Over Screen](https://raw.githubusercontent.com/cmulay/Arduino-Dinosaur-Game/master/img/img1.jpg)
