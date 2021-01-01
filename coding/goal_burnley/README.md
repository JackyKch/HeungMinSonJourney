### Plotting Son's amazing goal vs Burnley

> ## Context
December 7, 2019. Tottenham Hotspur Stadium. Spurs 2. Burnley 0. First Half. 31st minute. Son takes the ball 80km away from the goal. This is what happens next :

![SonGoal](https://i2.chinanews.com/simg/cmshd/2020/12/12/39b34779b2e5417687fd5ef585eb56a7.gif)

Son produced a wonderful a wonderful solo effort, running 86 meters from his own penalty area to the opposite goal in less than 12 seconds and 11 touches while eliminating more than 5 Burnley players.

> ## Objective
Using MatPlotlib and FC Python's Event Tagger, I tried to reproduce Son's route to the goal with a new plot at each touch. Adding touches one by one, we get at the end a representation of the goal with multiples plots that I saved in png files. With that I created the following video :

![SonGoalPlotted](https://github.com/JackyKch/HeungMinSonEvolution/blob/master/coding/goal_burnley/goalvideo.gif)

> ## Possible Improvements 
- One way to improve would be to add a delay between each plot that would match the delay between each Son's touches.
- Another way to improve this would be to use directly the goal's video and collect the coordinates in live directly from the video using object tracking.
