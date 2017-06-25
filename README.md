# SnakeGame

Step 1 - Go to this link: http://snakejs.netne.net/home.html
Step 2 - Press Start to Play. 
Step 3 - Use Arrow Keys to change direction. 
Step 4 - ???
Step 5 - Success!

OOP Principles

Classes and instances:

Classes and instances are two different things but are confused to be the same from time to time. A class is seen as a blueprint for your instances. What this means is that every instance you make is going to have the same attributes/properties as the other instances with the same classname. In my code this is represented in many diffrent ways. Instead of writing code seprately for every single class you can use a separate class to give every single instance of this class the same properties, with you having to write the code of these 3 properties only once.

Encapsulation:

Encapsulation is the principle where you portion off your properties with private, public or protected. All of my properties are portioned off in one of these three ways.

Composition:

Composition is the principle where a property has other properties. In my game this is shown in multiple ways. My start has a game, my game has a ball, paddle, bricks, life and game over and my game over has a start. Also life has a game over aswell.

Inheritance:
Inheritance is just what the name implies a class inherits properties form a general class and can use its properties while they are private for others. The only reason why the gameOver class is not a child of Figure is because they have a special condition that the figure can't produce.

Class diagram: 
https://camo.githubusercontent.com/fb5ab64cc82064f5f9668de5fa6501ed6a02348a/687474703a2f2f692e696d6775722e636f6d2f4c59364b704e742e706e67
