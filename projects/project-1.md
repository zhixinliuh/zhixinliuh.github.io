---
layout: project
type: project
image: images/guessresize.png
title: Number Guessing Game
# All dates must be YYYY-MM-DD format!
date: 2017-09-01
labels:
  - Javascript

Back in highschool builded an simple number guessing game for 2 player in STEM
one person enter a number between 1-6
the other person guesses what number they pick. 
guess the right number wins.

This is the code and jsfiddle site link
"https://jsfiddle.net/zhixinli0904/pmyrh817/2/"
```js
//create a variable for the first person
//number must not exceed 6
//create a variable for the second person
//number must not exceed 6
//compare both values
//if player 2 guess the same as player 1, tell player 2 he or she won.
//obviously, if the guess is wrong, player 2 loses
var player1 = prompt("pick a number, must not exceed 6");
if ((player1 < 1) || (player1 > 6) || (isNaN(player1))){
	window.alert("you cannot follow directions");
}
else {
	var player2 = prompt("guess a number 1-6");
  if (player1 == player2){
  window.alert("you win!");
  }
  else{
  	window.alert("person one answer was" +" "+ player1);
    window.alert("you chose"+" "+player2);
  }
}
```


