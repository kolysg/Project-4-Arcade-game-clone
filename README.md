## **ARCADE GAME CLONE: AN ANT'S QUEST** 

An html5 game inspired by "frogger".

### Game Instructions
---
The game will start automatically when the screen loads. You are an ant collecting food for your nest to survive a hard winter, collect as many leaves, cherries and gems as you can without colliding with those mean enemies that will harm you! You only have 10 lives, use them wisely.

You can move your character by pressing the `up`, `down`, `right` and `left` keys. Depending on the surface, the player will have different speeds (It will move **faster** in stone and **slower** in water). Your goal is to collect the necessary score for each level by reaching collectible items that will add to your score counter. 

Once you reach the necessary score for the current level, you can walk to the star located at the top right corner of the screen and move on to the next level. 

##### Collectible items
They add to your score. 
 
* Leaves = 5
* Cherries = 10
* Gems = 30

##### Counters
* **Lives** = keeps track of your lives.
* **Level** = displays the current level you are in.
* **Score** = displays your score for the current level.
* **Score needed** = displays the score you have to collect to pass to the next level if you reach the star (not the total score across all levels, only the score collected on the current level). 

   * _(**NOTE:** if this counter is not 0 and you reach the star, the player will go back to its initial location and you won't move on to the next level, you will have to collect the missing score)_

######Minimum score collected on each level to move on to the next level:
    * Level 1 needs a minimum of 110 points.
    * Level 2 needs a minimum of 210 points.
    * Level 3 needs a minimum of 410 points.

* **Total score** = keeps track of your _total_ score across all levels.


##### Enemies
Don't collide with bugs, frogs, spiders or snakes!!! they will hurt you. Each time you do, your player will lose 1 life and 4 points and it will go back to its initial location. (WARNING: Spiders are very dangerous, you will lose **2** lives if you collide with them)
. 
##### Winning and losing
If you succesfully complete all levels, a screen will appear showing your total score. If you run out of lives, you will lose and you will have to start again.

### Installation
---- 
The game doesn't require any installations or additional software. You only have to click on `index.html` and the game will execute on your browser. 

### License and Copyright
---
* This is a project for Udacity "Front End Web Developer" nanodegree.  
* Images were provided by Udacity, except [Ant](https://pixabay.com/es/hormiga-asusta-insectos-asustado-44589/), [leaves](https://pixabay.com/es/arce-oto%C3%B1o-de-la-hoja-orange-tonos-150741/), [Cherries](https://pixabay.com/es/cereza-madre-frutas-rojo-madura-575547/), [Frog](https://pixabay.com/es/rana-anfibios-tropicales-selva-46393/), [Snake](https://pixabay.com/es/serpiente-amarillo-p%C3%BArpura-reptil-46139/) and [Spider](https://pixabay.com/es/ara%C3%B1a-horripilante-ar%C3%A1cnido-miedo-311548/).  ([Pixabay.com](pixabay.com))  They are all licensed under [CC0 creative commons](https://creativecommons.org/about/cc0/)  
* Sounds were downloaded from [opengameart.org](opengameart.org)
    * [death.wav](http://opengameart.org/content/oldschool-win-and-die-jump-and-run-sounds) and [round_end.wav](http://opengameart.org/content/oldschool-win-and-die-jump-and-run-sounds) are licensed under public domain. Their autor is sauer2. 
    * [Accept.wav](http://opengameart.org/content/ui-accept-or-forward) is licensed under creative commons. Its author is 
       ViRiX (David McKee)