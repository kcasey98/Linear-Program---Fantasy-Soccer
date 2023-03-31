# Linear-Program---Fantasy-Soccer

The Premier League is the top division of soccer in Great Britain. And like many sports leagues, the Premier League has its own fantasy sports game called FPL. I myself play FPL and have been playing it for years. I look at my fantasy almost every single day and I’m constantly checking players points and different ways I can improve my team. When I first started playing FPL ten years ago, I wasn’t very good. I am a massive soccer fan and I know a lot about the game and the league. However, there is more to being good at FPL than knowing soccer. I realized this when World Chess Champion Magnus Carlsen finished 10th place back in 2019 where at one point he was in 1st place out of the 7 million teams. How could Magnus Carlsen be so good at fantasy? He doesn’t know anything about soccer. At that moment, I realized the secret to success: data.

I started using websites that tracked players' value, essentially a stock market for the game. You are given one transfer a week, so you can swap a player you don’t want. So before swapping a player, I would see if their value went up. If a player is purchased by a certain number of people, i.e. if the percentage ownership of the player increases, his price goes up. You are initially given $100, but if you purchase wisely, the value of your time rises. So instead of just buying players I felt were skilled and were likely to succeed in upcoming fixtures, I also focused on buying players whose values were to increase, so I could grow the wealth of my team. I also learned that if your player grows from $7 to & $7.4, and you sell them, you only get $7.2. You only keep half the earnings. And if it’s an odd number you round down so $7 to $7.5 would also sell for $7.2. Understanding the data and math behind the game took my team to another level. I am currently in the top 5% in the game, however I want to improve and I think this project is a great way of doing it.
Variables to consider for each player: points, position, team, price, % ownership

Constraints: Three players max from one team, $100 initial budget, 15 players on a given team (2 GK, 5 DEF, 5 MID, 3 FWD)

# My approach
I use linear programming and considering many constraints. In my code, I assemble a team that would maximize points over the course of a season. However, I am considering different optimization variations that can change results greatly.

Variables that I consider:

Wildcard: You can completely change your team once during the season

Captain: Each week you captain one player which doubles there points

Starting 11: You have a team of 15, but you can only play 11 on a given week and that 11 can swicth each week
