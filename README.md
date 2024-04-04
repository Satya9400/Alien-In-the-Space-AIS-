# Alien-In-the-Space-AIS-
This is beginning of my coding and learning programing languages.
Today’s generation is totally attracted to multiplayer games and e-sports.
So, from there I decided to create offline video game. In this game I used HTML and some basics of CSS. 

In this game you have to kill aliens using mouse (right click). Aliens will move in your system’s screen, you have to adjust your cursor towards the alien and kill using right click. After finish one game you can restart and can play another and another game, how much you want.

I have also used some images like Alien, background. <label for="alienInput1" class="alien alien1">
                                                      <img src="alien.png">
Images are also attached in this repository.
To make number of aliens i have used <input class="input input1" id="alienInput1" type="radio"> and incrased the number of inputs to increase the number of aliens.
To make movement of the aliens i have used @keyframes move{
0%{
    left:0%;
    }
20%{
    left:20%;top:50%; 
    }
40%{
    top:30%; left:90%;
    }
60%{
    top:80%; right:80%;
    }
80%{
    top:10%; left:20%:
    }
100%{
    top:30%; right:20%; 
    }
    and i also added the animation delays.
