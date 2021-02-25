## Summary

A game to be played on a mobile device. The game will have several containers of different colored objects in each. The goal of the game is to sort all colors in to the objects so they only have one of each color in each container. You can only move one object at a time and each container can only hold a maximum of 5 objects at a time.

## Intended users

* People who use public transportation or spend a lot of time with free time on their hands

 As a person who has free time on their hands during long bus rides, I would like to have a game to play on my phone that is easy to pick up and put down to make the bus rides feel shorter.

* Someone with Children

 As someone who has children, I like to give them my cell phone to keep them occupied when they need to be still and quiet. This game can achieve that while also making their brains work a little while they figure out the puzzles.

## Client component

* **Functionality**

    The user will be able to log in through a cloud service to keep track of their levels passed even when playing on other devices, as well as see their scores, and relevant stats.
    Once logged in the player will be able to start playing the game. The game consists of several "containers" with colored objects in them of varying colors. The user will have to sort the colored objects so that they are all in containers with only objects of the same color. The user can only move one object at a time, each container can hold a maximum of 5 objects at a time, and when moving the objects the user can only place the object on another object of the same color. 
    There will be a settings page where users can change their display name, or google sign in information. There will also be a page to display stats, such as what level the user has reached, along with time stamps, and moves used to see how quickly they've gone through each level. 
  
* **Persistent data**

     The app will store the levels the player has reached even while not connected to the internet, and the player will be able to access and continue to play the game and levels.

* **Device/external services**

    Google Sign in

## Server component

* **Functionality**

    The servers will have to randomize the placements of the colored objects in the containers, progressivly increasing the difficulty of the levels.
    
    Users will be able to access their current level and stats from other devices after logging in.

* **Persistent data**

    Levels passed, current level, time it took on each level, and moves taken in each level. 
    
* **External services**

    https://developers.google.com/identity/sign-in/web
  
 
## Stretch goals/possible enhancements 

Having music playing in the game and noises when things are moved or interacted with.

Add a facebook log in component, this would allow users to see the levels their friends have gotten to along with their statistics.

Add a leaderboard component for users to compare scores with other users using google sign in.