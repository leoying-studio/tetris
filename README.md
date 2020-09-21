# tetris
tetris 俄罗斯方块

## 快速开始
```
   
   <div id='tetris'></div>
   
   const tetris = new Tetris('#tetris);
   tetris.start(300);

```


## 分数
```
   <heaer>
		<span id="score"></span>
   </header>
   <div id='tetris'></div>
   
   const tetris = new Tetris('#tetris);
   tetris.on('score', function(score) {
	   document.getElementId('score).innerText = score;
   })
   tetris.start(300);
```