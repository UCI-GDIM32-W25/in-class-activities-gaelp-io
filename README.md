# GDIM32 In Class Activities
## Week 1 In Class Activity

### Actvity 1

My table discussed various methods to be able to ace this class, one being to make sure you attend the lectures so that you are able to ask any questions you may have about the topic being discussed. As well as doing the pre-learning so that you don't fall behind your peers and that you know what you will be learning in the next lecture. It's also important to ask any pressing questions right away instead of waiting because waiting too long could lead to getting a solution too late or not getting a solution at all.

### Activity 2 

Q1: The value of x after those lines of code would be 10.

Q2: The value of x is 2, this is a loop so everytime x is less than 2 it adds 1, then once x reaches the value of 2 the loop stops.

Q3: This line of code enters the phrase "hello world" into the debug.log that can be seen in Unity when playtesting your current game.

Q4: The classes they are usable in are MonoBehaviours, so the ??? should be replaced by "MonoBehaviour".

Q5: Private void start is what starts the line of code and Print message(10) essentially makes 10 the value the next line of code will use since it is an argument. So when it says Debug.log("x =" + x); then the console will show x = 10 in the debug log.

Q6: 10 is the argument or value being assigned to print message while "x =" + x is a string which the argument/value 10 is being sent to.

Q7: Transform should not just be "Transform" in the line "Transform.Translate(_direction);".

Q8: We should change "Transform" to "_playerTransform" so that it is referring to that specific GameObject

### Activity 3

[MG1 Breakdown Google Doc](https://docs.google.com/document/d/1y5LOXHts-EvqE00ku0UjBCC5AgohWl3lteMNVPOctuo/edit?tab=t.0)

## Week 2 In Class Activity

### Activity 1

![in class activity](https://github.com/user-attachments/assets/f7ec7a63-e29d-4f5a-9744-6fc001a5af6d)

### Activity 2

[Added Penguin and it can jump](https://github.com/UCI-GDIM32-W25/mg2-gaelp-io/commit/d77123579b72f8219ddd97ef919c6ea2d7040f79)
Here I added the penguin/player gameobject by adding a sprite renderer, choosing a sprite of a penguin sliding, a rigidbody 2D, and a box collider 2D. I also made it so the penguin has a player script so that when you press space it jumps!

## Week 3 In Class Activity

### Activity 1
Buddy Name: Jeremiah Yang

### Activity 2
Buddy Name: Jeremiah Yang

### Activity 3
![IMG_1973](https://github.com/user-attachments/assets/3ce3c7d4-8ad8-474a-848d-bcff6de54568)

## Week 4 In Class Activity

### Activity 0
Buddy Name: Jeremiah Yang

### Activity 1
When I run the game with multiple Locator gameobjects, the scripts for all of the Locator gameobjects except for one destroy themselves.

### Activity 2
![In class activity drawing](https://github.com/user-attachments/assets/de9b8df7-4e45-4583-b4e5-4b23fcd37998)

### Activity 3
[Added bird, grass, and fixed aspect ratio](https://github.com/gaelp-io/HW4/commit/12c80ea3195fb09874147855bc37950c6a448e98)
I added the sprites for the bird, pipes, and grass, as well as physically added the playe game object with the bird sprite and box collider 2D and the grass as terrain that also has a box collider 2D.

## Week 5 In Class Activity

### Activity 1
I would probably keep the design of these interfaces and abstracts the same since IBreakable holds multiple methods to call for when an item gets damaged and then ultimately breaks once its durability reaches 0 or less since each class inherits from IBreakable. With the abstract class, each item can simply call the use method since they inherit from Item. Since IBreakable is an interface class it also allows the items to inherit from both the abstract Item class and the IBreakable interface class.

### Activity 2
The classes like public class ItemW5Demo2 : ScriptableObject act as the model since they are the code and data of the scriptable objects. However, the CreateAssetMenu is the controller since in Unity it shows up in the inspector and allows you to change specific attributes of a scriptable object like health, names, and even dialouge lines. The View part would be the text that pops up whenever a player opens their inventory (which shows their items) and whenever they get near an enemy where they will then play their dialouge line and have it pop up as text.

### Activity 3
#### Scenario 1
The design patterns that would work best for this scenario would be a singleton to act as the game controller and inheritance with polymorphism since abstract classes would work best here. Abstract classes would be used to make a common class that all child classes would need to use their methods from, and then within the child classes we can specify their attributes depending on what type of beat they are. An abstract class would make the most sense since we want to implement shared behaviour and member variables for the child classes. An example of an abstract class in a rythm game could be public abstract class hit where the method inside would be labeled beathit or something similar so that each child class would need to implement that method since all beats need to be hit and need to determine what happens if they are hit or not.

#### Scenario 2


#### Scenario 3


### Activity 4
Attendance: Gael Porras, Jeremiah Yang

Proposal: [Final Project Proposal First Draft](https://docs.google.com/document/d/1-4LVGJgfxqEb7zRdfGDfO5tOJxruOldH0SpWawnbftE/edit?tab=t.0#heading=h.wcm5jag04eng)