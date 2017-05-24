# chess-engine-analysis
Curious to determine the most valuable via a blitz chess tournament (5 minutes) between the same engine where time allocations for moves differ between contestants as the game progresses, specifically during the opening, mid-game, and endgame

### hypothesis
- getting of to a good start is likely going to be crucial and overpowering, plus excess time could help in endgame

### testing procedure
- based on my estimate of games typically lasting around 50 moves
- default move time will be 1 second
- opening advantaged player will have 5 seconds to think during moves 0-10
- mid-game advantaged player will have 5 seconds to think during moves 10-25
- end-game advantaged player will have 5 seconds to think during moves 25-50+

### notes
- 5 seconds are optional, don't neccesarily have to be used as time is a resource
- chess engine will be lastest version of stockfish
- computer will be optimized for game engine
- move times subject to change based on testing (current times don't take much time..., maybe 2 seconds default)
