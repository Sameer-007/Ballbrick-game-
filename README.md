# Ballbrick-game-
Ball brick is a game where there will be a ball at the ground level and with that ball you have
to destroy all the bricks above it. For each hit the bricks will come closer to ground level.
When the ball touches the ground then you lose GAME OVER..!! If you destroy all the bricks
before the bricks touches the ground then you win HURRAY..!!
# Instructions :
Consider the game in a NxN Matrix.The first ball starts from the middle of the bottom most
row of the matrix.The ball can traverse in three directions. Straight(ST), Left Diagonal(LD)
and Right Diagonal(RD). The user has to enter the direction in which the ball has to
traverse. After getting the input from the user the ball will traverse in that direction and hit the
brick/wall on its way. The bricks can be arranged in any manner and the bricks strength will
be denoted by a number.
Note:
● When the ball hits either the left or the right wall then the ball will traverse horizontally
either in right or left direction respectively. If it hits any bricks then the ball traverse
down straight to the ground level.
● If the ball hits both wall continuously without hitting any brick then the ball is lost and
the ball has to return to its inital position (Center of the bottom most row) and the ball
count is decremented..
● And also the ball count is decremented if it doesn't return to the same position it
started.
● If all the bricks are broken before the ball count is reduced to 0 then you are the
winner or else game over.
● When the ball hits the top wall, the ball travels straight to the ground unless if there
are no bricks while the ball is traversing down.
# Terminologies:
G - Ground Level.
W - Wall.
o - Ball.
