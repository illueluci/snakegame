# snakegame
from https://www.youtube.com/watch?v=8dfePlONtls

modifications :
-out of bounds check
-prevention of moving backwards (if snake is going up, cannot go down). Still not completely foolproof, sharp u-turn is possible (and obviously causes game over)
-music now loops
-golden apple successfully implemented since 26/03/2022! 1 golden apple = 5 apple, appears every 10 regular apple eaten
-changed "pygame.time.wait" with "pygame.clock.tick(10)", game runs at 10 fps by default. more fps = speedy snek

