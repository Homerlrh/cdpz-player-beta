# Project Code Prez - Player
Code Prez is an all-in-one solution that aims to revamp coding tutorials, by creating a new dynamic between the student and the content.

It contains two parts,  a free and accessible platform for creators to create their documents on, PLUS an NPM package for them to share their amazing tutorials on their own platforms.

This repo is source code of the player.

## Installation
````
npm install cdpz-player-beta 
````

## Props
- content: Code Prez generated cdpz text file
- audio: CodePrez generated weba audio file
  
## How to use
```
import React from "react";
import Player from "cdpz-player-beta";

function App() {
  return (
   <div className="App">
       <Player content={content} audio={path/audio}/>
    </div>
  );
}

```



