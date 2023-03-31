# jelly-cube.github.io

### _one out of 1.98 billion websites_
just a tiny little corner of a vast planet called the **internet**

## Socials
<a href="https://discord.gg/8ahaWYpD9P"><image src="https://cdn-icons-png.flaticon.com/128/2111/2111370.png" width="35" height="35"><strong style="font-size: 24;"> Our Discord (RSIN)</strong></image>

<a href="https://www.reddit.com/user/dumb_idiot2r2"><image src="https://cdn-icons-png.flaticon.com/128/3670/3670226.png" width="35" height="35"><strong style="font-size: 24;"> Our Reddit (u/dumb_idiot2r2)
</strong></image>

<a href="https://twitter.com/AlexLiu00142896"><image src="https://cdn-icons-png.flaticon.com/128/3256/3256013.png" width="35" height="35"><strong style="font-size: 24;"> Our Twitter (@AlexLiu00142896)</strong></image>
  

### Guilded server:
   
<iframe src="https://www.guilded.gg/canvas_index.html?route=%2Fcanvas%2Fembed%2Fbadge%2FWlozqg8R" width="182" height="48" frameborder="0" scrolling="no"></iframe>

### Discord server:

<iframe src="https://discord.com/widget?id=1048717659753173064&theme=dark" width="750" height="500" allowtransparency="true" frameborder="0" sandbox="allow-popups allow-popups-to-escape-sandbox allow-same-origin allow-scripts"></iframe>
   
You might be just one out of ~100 people to land on this webpage

### the chances of you landing on this website

**are a billionth of 50%**
in percentage form, this is around **0.00000000505051%**

So if you just so happened to stumble across this website; 
you are one out of millions to do so!

`so congratulations! ;)` 

every single webpage is just a tiny rock stranded in a entire

sea of information and raw data.
# For more information visit:
##    [fjhlgfkjhlfjhlfjhlkjl](https:/jelly-cube/jelly-cube.github.io/figdizzsittt.md)


There is also an ocean of websites out their- just waiting to be discovered.



### this website was made by... **Drippie#2667** (feel free to add/DM me on Discord!)

**about me**: hello. 

- `just an amateur coder on github`

- `Knows HTML and a bit of shell commands.` 

   - and probably nothing else 

   - ~has 2 brain cells left.

 - open for contact at main email: **alex.yt2021.io@gmail.com**

 - any pronouns work on Discord 
   
 <head>
	<title>Tic Tac Toe</title>
	<style>
		* {
			box-sizing: border-box;
			font-family: Arial, sans-serif;
		}

		body {
			display: flex;
			flex-direction: column;
			align-items: center;
			margin-top: 50px;
		}

		.board {
			display: flex;
			flex-wrap: wrap;
			width: 300px;
			height: 300px;
			border: 1px solid black;
		}

		.square {
			display: flex;
			justify-content: center;
			align-items: center;
			width: 100px;
			height: 100px;
			font-size: 50px;
			cursor: pointer;
			border: 1px solid black;
		}

		.square:hover {
			background-color: #eee;
		}
	</style>
</head>
<body>
	<h1>Tic Tac Toe</h1>
	<div class="board"></div>
  <script type="text/javascript"> 
  const board = document.querySelector('.board');
const squares = [];

// Create the squares and add them to the board
for (let i = 0; i < 9; i++) {
    const square = document.createElement('div');
    square.classList.add('square');
    squares.push(square);
    board.appendChild(square);

    // Add event listener to each square
    square.addEventListener('click', () => {
        if (!square.textContent) {
            square.textContent = turn;
            checkForWin();
            toggleTurn();
        }
    });
}

let turn = 'X';

// Toggle between X and O
function toggleTurn() {
    turn = turn === 'X' ? 'O' : 'X';
}

// Check if there is a winner
function checkForWin() {
    const lines = [
        [0, 1, 2],
        [3, 4, 5],
        [6, 7, 8],
        [0, 3, 6],
        [1, 4, 7],
        [2, 5, 8],
        [0, 4, 8],
        [2, 4, 6]
    ];

    for (let i = 0; i < lines.length; i++) {
        const [a, b, c] = lines[i];
        if (squares[a].textContent && squares[a].textContent === squares[b].textContent && squares[a].textContent === squares[c].textContent) {
            alert(`${squares[a].textContent} wins!`);
            resetBoard();
        }
    }
}

// Reset the board
function resetBoard() {
    for (let i = 0; i < squares.length; i++) {
        squares[i].textContent = '';
    }
    turn = 'X';
}
  </script>

 my OG website: [https://memestonks.github.io](https://memestonks.github.io)

 my github profile: [https://github.com/jelly-cube?tab=overview&from=2023-02-01&to=2023-02-19](https://github.com/jelly-cube?tab=overview&from=2023-02-01&to=2023-02-19)

### external soundtracks **[NCS releases]**
 
<iframe style="border-radius:12px" src="https://open.spotify.com/embed/playlist/3nI2Bkuxxzr1pY1H0cgQqo?utm_source=generator" width="100%" height="352" frameBorder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>

<iframe style="border-radius:12px" src="https://open.spotify.com/embed/playlist/49APwudtUCYjMzBBjNCn0g?utm_source=generator" width="100%" height="352" frameBorder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>

   [animation](https:/jelly-cube/jelly-cube.github.iogh-pages/fwdk.html)

#### **See you later!**

[animation of some random floating green cube spinning around](/animation.html)

but with no outlines and 420hp animation quality

**source of 3d javascript/html:** [https://threejs.org/docs/index.html#manual/en/introduction/Creating-a-scene](https://threejs.org/docs/index.html#manual/en/introduction/Creating-a-scene)
threejs: https://threejs.org/build/three.js
(@license Copyright 2010-2023 Three.js Authors
 SPDX-License-Identifier: MIT)
