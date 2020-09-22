# tetris
tetris 俄罗斯方块

## 快速开始
```
   
   <div id='tetris'></div>
   
   const tetris = new Tetris('#tetris);
   // 执行速度为300毫秒
   tetris.start(300);

```


## 分数
```
   <header>
	<span id="score"></span>
   </header>
   <div id='tetris'></div>
   
   const tetris = new Tetris('#tetris);
   tetris.on('score', function(score) {
	document.getElementById('score).innerText = score;
   })
   tetris.start(300);
```
