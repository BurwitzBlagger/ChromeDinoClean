1.Normal state save
var normalDino = Runner.prototype.gameOver 
2.  Immortality
Runner.prototype.gameOver = function (){} 
3. Speed (replace 1000 with the value you want)
Runner.instance_.setSpeed(1000)
4. Immortality cancel
Runner.prototype.gameOver = normalDino
note: #4 won't work without #1, and you should do #1, #2, #3, #4 in order (depends on what you want)
