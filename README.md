**CircuitPython code to create a touch screen math drill box. **

HARDWARE
--------
 Adafruit Feather RP2350
 
 3.2" ILI9341 SPI TFT LCD Display Touch Panel 320x240 TFT LCD Touch Screen - XPT2046 Touch Controller
 
 DS3231 RTC Module
 
 Neopixel LED (1)
 
 SD Card
 
 Piezo buzzer
 
 ----------------------------------------------------------------------

GAME PLAY
---------
The player touches the START button to begin a game. First they are prompted to select their name from a pre-populated list. If their name isn't listed they can touch NEW which will open a 4x4 grid of buttons where they can enter their name. Once the name is selected then the player chooses the type of problems (Addition, Subtraction, Multiplication or Mixed). After selecting the type of problem the player then chooses how many problems in the game (10, 20, 35, or 50). From there the game starts. The problem is shown on the screen and four choices are available. If the player chooses the correct answer the neopixel turns green, a short high beep sounds and the game moves to the next problem. If they answer incorrectly a low beep sounds, the neopixel turns red and the screen remains allowing the player to try again. Players can also skip the problem by touching the Next button, the neopixel with beep twice, the neopixel turns yellow and the game moves to the next question. When the selected number of problems is reached the game moves to score displat.

SCORING
-------
The game tracks correct answers as well as average time per problem. The score is weighted 70% accuracy and 30% time. Scores are recorded on the SD card and high scores are displayed. There are also various scoreboards available at the end of the game to display stats by player. 

