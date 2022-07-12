# React_Tenzies-game
## Table of contents
* [App Link](#app-link)
* [General info](#general-information)
* [Stretch Goals](#stretch-goals)
* [Technologies](#technologies)
* [Add Features](#add-features)
<br>

## App Link
https://fun-tenzies-game.netlify.app/
<br>

## General information
<img src="https://user-images.githubusercontent.com/99662300/178423065-e57e4ca1-e472-4a66-b0c2-b56d2062f762.png" width=45% height=45%>

This game application was built based on React, with: 
- Component
- Props
- State
- Hooks

2 significant hooks are used here : useState, useEffect.
<br>-  __useState__: 
<br>state will hook into the component
- [dice, setDice] ==> manage die number
- [tenzies, setTenzies] ==> manage state whether user win the game

<br>- __useEffect__: 
<br >it can be the place to side effect code (for instance, fetch data from API) 
<br> However here it is used to sync 2 internal states.

<br>Add __events listeners__ :
- to freeze die
- Roll / get the new game

<br>

## Technologies
- React
- HTML
- CSS
- JSX

<br>

## Stretch Goals
- As a user, they can start the game whenever they wish to.
- As a user, they can held the die and roll until all dice are sam value.
- As a user, there will be a Confetti without the cleanup waiting for thier win.

<br>


## Add Features
- As a user, they can review the time and the number of rolls they palyed in each game round.
- As a user, they can always review their best time which has saved to localStorage, the data will not expire even close the game.


