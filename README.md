# BIRB-STOP

## Description
Birb Stop is a game where the player has to, well, stop their bird from destroying their carefully organized stack of things. After 20 seconds surviving, the speed intervals randomize themselves and get quicker for higher difficulty. If you survive 1 minute you win the game. If the bird gets to pass your barrier, it’s game over.


// ## MVP (DOM - CANVAS)
This is a game where the player uses a barrier to stop the enemy bird from getting to the tower.
--------

## Backlog
-- Timer
-- Lives
-- Harder mode ‘left + right’
-- Harder mode ‘left + right + up’
-- Game over screen specifically for the ‘left + right’ mode
-- Game over screen specifically for the ‘left + right + up’ mode


## Data structure

### main.js
```

buildSplashScreen(){
}

removeSplashScreen(){
}

buildGameScreen(){
}

removeGameScreen(){
}

buildGameOverScreen(){
}

removeGameOverScreen(){
}

```

### game.js
```
Game(){
  this.canvas;
  this.birdEnemies;
}

Game.prototype.start = function(){
}

Game.prototype.startLoop = function(){
}

Game.prototype.checkCollisionsToTower = function(){
}

Game.prototype.checkCollisionsToPlayer = function(){
}

Game.prototype.setGameOver = function(){
}
```

### player.js
```
Player(){
  this.canvas;
  this.x;
  this.y;
  this.width;
  this.height;
  this.speed; 
  this.direction;
}

Player.prototype.draw = function(){
}

Player.prototype.updatePosition = function(){
}


```

### bird.js
```
EnemyBird(){
  this.canvas;
  this.x;
  this.y;
  this.direction;
  this.speed;
  this.width;
  this.height;
}

EnemyBird.prototype.updatePosition(){
}

EnemyBird.prototype.bounceBack(){
}

EnemyBird.prototype.draw(){
}

```

### tower.js 
```
Tower(){
  this.canvas;
  this.x;
  this.y;
  this.width;
  this.height;
}

Tower.prototype.draw(){
}

```


## States and States Transitions
```
- splashScreen()
  - buildSplash()
  - addEventListener(startGame)
  
  
- starGame()
  - create new Game()
  - game.start()
  
  
- gameOver()
  - buildGameOver()
  - addEventListener(startGame) 
```

## Task
- Main - buildDom
- Main - buildSplashScreen
- Main - addEventListener
- Main - buildGameScreen
- Main - removeGameScreen
- Main - buildGameOverScreen
- Main - addEventListener
- Main - removeGameOverScreen
- Game - startLoop
- Game - checkCollisionsToTower
- Game - checkCollisionsToPlayer
- Game - setGameOver
- Game - addEventListener
- Player - draw
- Player - updatePosition
- EnemyBird - draw
- EnemyBird - updatePosition
- EnemyBird - bounceBack
- Tower - draw

## Links


### Trello
[Link url](https://trello.com/b/P8V3S9Pm)


### Git
URls for the project repo and deploy
[Link Repo]
[Link Deploy]


### Slides
URls for the project presentation (slides)
[Link Slides.com]



