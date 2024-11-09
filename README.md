# Assignment-13
 
Basic Programming in C# (OOP 1)
Create the Player Class (Non-MonoBehaviour):
1. Create a C# script named Player without “: MonoBehaviour” and
remove the Start() and Update() methods.
2. Define the following public fields:
a. playerName (string)
b. health (int)
3. Implement a method InitializePlayer(string name, int initialHealth)
to set the playerName and health.
4. Add a method Heal(int amount) to increase health by a specified
amount and print the update using Debug.Log().
5. Overload the Heal() method to accept a bool fullRestore parameter
to fully restore health when set to true.
6. Add a static field playerCount to keep track of the number of Player
objects.
7. Increment playerCount within the InitializePlayer() method.
8. Create a static method ShowPlayerCount() to print playerCount
using Debug.Log().
Create the GameManager Class with “: MonoBehaviour”:
1. Attach GameManager to a game object in your Unity scene.
2. In the Start() method:
a. Instantiate two Player objects.
b. Call InitializePlayer() to set playerName and health for each
Player object.
c. Use both versions of the Heal() method to demonstrate method
overloading.
d. Call ShowPlayerCount() to display the total number of Player
objects.
