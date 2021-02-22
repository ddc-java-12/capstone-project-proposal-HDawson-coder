## Summary

A game to be played on a mobile device. The game will have several containers of different colored objects in each. The goal of the game is to sort all colors in to the objects so they only have one of each color in each container. You can only move one object at a time and each container can only hold a maximum of 5 objects at a time.

## Intended users

* As a person who has free time on their hand during long bus rides, I would like to have a game to play on my phone that is easy to pick up and put down to make the bus rides feel shorter.

* As someone who has children, I like to give them my cell phone to keep them occupied when they need to be still and quiet. This game can acheive that while also making their brains work a little while they figure out the puzzles.

## Client component

* **Functionality**

    The user will be able to sign in through a cloud service to keep track of their levels passed even when playing on other devices, as well as see their scores against other friends by logging in through Facebook.
    Once logged in the player will be able to start playing the game. The game consists of several "containers" with colored objects in them of varying colors. The user will have to sort the colored objects so that they are all in containers with only objects of the same color. The user can only move one object at a time and each container can hold a maximum of 5 objects at a time. 
    There will be settings to edit their log in settings, add friends to see their scores, edit noise/music settings.
  
* **Persistent data**

     The app will store the levels the player has reached even while not connected to the internet, and the player will be able to access and continue to play the game and levels.

* **Device/external services**

    Unsure.

## Server component

* **Functionality**

    The servers will have to randomize the placements of the colored objects in the containers, progressivly increasing the difficulty of the levels.

* **Persistent data**

    The leaderboard (levels reached) will be in the persistent data. Players will be able to access their log in and resume play from beaten levels when logging in across platforms. They will also be able to see friends and others high scores.
    
* **External services**

    https://developers.google.com/identity/sign-in/web
  
 
## Stretch goals/possible enhancements 

Potentially having music playing in the game and noises when things are moved or interacted with.