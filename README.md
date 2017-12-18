# Rutgers Roundabout
Choose Your Own Adventure game written in Java, which was a final project for IT 202: Object-Oriented Programming at Rutgers University.

### The Concept
This game puts you in the shoes of a prospective student for Rutgers University - The State University of New Jersey and going through a journey through the campuses of Rutgers. You will be traveling from Douglass, to Busch, to College Ave, and to Livingston by doing different tasks. Doing these tasks will either bring you closer to being admitted into Rutgers or hurt your chances!

### How to Play
You will start off by saying how many players there are. 
Next, you will each be asked questions and you either reply yes or no (case does not matter). 
Your choices will either award or deduct points from you. 

Choosing correct answers will help you gain a random amount of points from 1-10.
Choosing incorrect answers will deduct a random amount of points from 1-10. 

If you can reach 15 points, you win admission! Best of luck on becoming a Scarlet Knight!

***** 

## Final Project: Assignment Details
The entire final project will be contained in a Java project named FinalProject and said project will contain:
- The PlayGame class which will have the following:
  1. Your main method that is used to start the game MUST be in this
class. Do not write all your game code within this main method.
  2. A prompt will appear when the game is over asking if the user
would like to play again
  3. This class interacts with the other classes in your project
  4. This class will start your game
- A StartAdventure class which will have the following:
  1. Contains the code used to create a new game object
  2. Creates the game “environment” whether it is rooms, campuses,
etc. and fills those environments. If for example, you have the
user answer questions, the questions should be generated by
this class
  3. Displays relevant information to the user, such as “you are here”
indicator
  4. Handles commands from the user (including those that cause
exceptions)
- A Player class which will
  1. Have all the relevant information you collect from the player such
as location, name, etc.

Your assignment is to write an adventure game with your group. It should have:
- A general location (campus, the mall, the library, etc.)
- The 3 classes listed above
- The option for more than one player
- At least 2 examples of Overridden Methods (will be covered under
inheritance)
- You MUST encapsulate your instance variables and use the least amount of
public methods necessary
- README.txt – that explains the game concept, how to play, and a “cheat
sheet” for me so that I can easily grade your assignment. This does NOT have
to be displayed in the game.
