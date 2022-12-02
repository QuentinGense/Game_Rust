# Game_Rust
/*Quentin Gense 02/12/2022*/
Game where two player fighting and can customize their stats and use potions and shields
/*All copies of the code not specifying the name of its creator or reflecting plagiarism and appropriation of the code will be followed by a trial*/

In this code you will find the notions of loops, conditions, object-oriented programming, string conversion, input and randomization.

In the first part of my code you will find the initialization of the structure of Player, it will be our player and we will declare the values of its stats so u8, usize and string.

We'll start by creating the player implementation but I don't recommend starting your functions now because you need to get your code working before that phase.

After that we can create our main, this is where all the code will be executed. We're starting to ask for the names of our players 1 and 2 because we need their names to populate the player_name values.

This moment passed, we can start to initialize our two players with the basic values which we need (if you need another value than the ones that I gave, you will have to change it but change it also in the class functions).

Now we are going to ask our players when they want to use their shield and convert their answer to u8 to use it at the right time with a condition.
Our game is about to start, but before our players need to customize their hero, we now call the stats function which is shown in the function part of the class. In this function, we will give the possibility to our players to customize their skills in hp, armor, dodges, attacks and crits. They will default to 10 points but you can give them more or less depending on your needs. Once the points have been awarded, we will ask our players one last time if they keep this distribution or if they want them reset.

The points are now distributed and the shield time initialized, so the fight can begin.

As long as one of the players does not reach 0 life points, the fight continues over and over again. If one of the players has medium HP, they can choose to use a life potion to regenerate their HP.

Once the fight is over, the winner of the fight is now declared or if the two players have found a fatal tie in their fight.
