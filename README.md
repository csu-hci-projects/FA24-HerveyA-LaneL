# FA24-HerveyA-LaneL

## Links for References:

<a href="https://www.youtube.com/watch?v=KOvesqHDrgg">Lab video 6: https://www.youtube.com/watch?v=KOvesqHDrgg</a>

<a href="https://www.youtube.com/watch?v=Sag2F-8ZQgM">Lab video 7: https://www.youtube.com/watch?v=Sag2F-8ZQgM</a>

<a href="https://www.youtube.com/watch?v=GP0LQgudYUc">Lab video 8: https://www.youtube.com/watch?v=GP0LQgudYUc</a>

<a href="https://www.youtube.com/watch?v=vO1i9Wcx4Xc">Health and Damage System Tutorial: https://www.youtube.com/watch?v=vO1i9Wcx4X</a>

<a href="https://www.youtube.com/watch?v=kumZj_mov58&t=23s">Main Menu Tutorial: https://www.youtube.com/watch?v=kumZj_mov58&t=23s</a>

<a href="https://www.youtube.com/watch?v=_p3rAlqevJ4">Health Pickup Tutorial: https://www.youtube.com/watch?v=_p3rAlqevJ4</a>

<a href="https://www.youtube.com/watch?v=uI5ps5DbFg">Target Damage System Tutorial: https://www.youtube.com/watch?v=uI5ps5DbFg</a>

## Game Video Links:

<a href="https://youtu.be/qWz5tkQL8FM">CS310H Homework 1 Game Walkthrough: https://youtu.be/qWz5tkQL8FM</a>

<a href="https://youtu.be/IGFp3e-CZ2s">CS310H Homework 1 Game Walkthrough: https://youtu.be/IGFp3e-CZ2s</a>

## Project Description:

This program is a First Person Shooter (FPS) game built in Unreal Engine, version 5.3.2. The game starts in a Main Menu level, where the player can choose to play the game or quit the application. If the player chooses to play the game, then level one will be opened, where the player is spawned in and will be required to shoot and destroy three targets in order to complete the level. In this level, there are poisonous mushroom trees that will damage the player whenever they come into contact with it. The player must thus avoid coming into contact with these trees while navigating their way through the forest to find and destroy the target crystals. Completing level one will then direct the player to level two, where they will be spawned in and have to shoot down 5 target crystals. This level also contains yellow mushrooms that will do damage to the player whenever the player comes into contact with it. Destroying all of the targets will lead the player back to the main screen where they can then choose to start over and play the two levels over again or they can quit the game and the application will close. Each level also contains health pickups and ammo pickups, which will replenish the player's health and ammo supply. The player's health is capped at 100, and the starting amount of ammo is 10. 

## Task Delegation:

Livia:
* Built and designed Level two.
* Created the initial menu and logic for the main menu. 
* Worked on making the Ammo pickups and adding that information into the UI. 
* Added a mechanic to track the amount of targets in the game and then change levels when all targets have been defeated. 
* Created an object blueprint to create an object that will do damage to the player.
* Created multiple types of objects that do damage based on that. 
* Debugged level two lighting.
* Packaged the game for submission.
* Worked on the ReadMe and the resources beyond this class document.

Ashly:
* Built and designed Level One.
* Implemented the Health Point (HP) system for the player with a max health of 100.
* Implemented the Health Point (HP) player UI.
* Implemented the damage system for the player that updates health based on hazard interactions.
* Implemented the Health Point (HP) system for target objects with a max health of 100. 
* Implemented the Health Point (HP) target UI.
* Created blueprints so that the player would respawn in the level when they died.
* Created blueprints so that the target would be destroyed when it ran out of HP. 
* Added in Health Point (HP) pickup objects so that the player would be able to get additional HP when they ran out, capped the HP at 100. 
* Debugged level transition blueprints.
* Worked on the ReadMe and resources beyond this class document.

## Resources Beyond This Class:

For this homework, we mostly used tutorials to help with our game implementation but we did sparingly use the LLM ChatGPT. For our Health Point (HP) and damage system, we were able to find a useful tutorial online that helped with the UI and blueprint logic that we were able to follow and apply a similar system to our player. We also used a tutorial to help implement our target HP system, which in our case were crystals. We again found another tutorial for the health pickups for our player which we took some of the logic from. We also relied on a tutorial for our main menu. All of the links to these tutorials are included in our references.

What we used ChatGPT for was for bug fixing our game when needed. For one, we ran into an issue when trying to design the logic for transitioning between levels. We had originally designed it to detect if the level was completed after each tick, but with the help of ChatGpt we were able to rework some of our logic to create a custom event once the number of targets left to hit was equal to zero. We also used it to help reload the level when a player dies by requesting basic instructions and bugfixes. We also used ChatGPT to figure out how to test our damage and reload systems by learning how to apply a damage and death event to the player over time. We also used ChatGPT to help define the requirements that would go into designing the damage system for the targets. Finally we used ChatGPT to help debug the lighting issues we were having on Level One. 


## Meetings with your group:

October 21st: Met in class and discussed our tasks/divided levels and chose a theme for our design. Delegated each person to choose assets and come up with a plan for their level prior to starting major development. 

October 23rd: Met in class and compared selected assets to make final selections on game themes and assets that would be used across both levels. Scheduled time to meet up later in the week to sit and work on the game for a large block of time to make sure both people understood how to use all of the aspects of unreal engine as well as version control with github desktop. 

October 25th: Met to work on building out our game, each worked on our individual levels and discussed responsibilities we would each complete on our own for the cohesive elements of the game (blueprints for the different game functions like hazards, pickups, and targets). 

October 30th: Discussed challenges with our development and came up with a plan to fix those challenges the next day by each completing all of the logic we assigned ourselves and preparing questions for eachother related to issues we encountered while developing.

October 31st: Met for finishing touches on game where we made sure all aspects of the project worked cohesively together. We also made the videos and reports based off of our finished project.
