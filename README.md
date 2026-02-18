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
Abstract classes would probably also work best here to have all characters have the same basic movement while allowing child classes to make more specific attributes for each character.

#### Scenario 3
States could be useful for planting, mining, or even growth states of each plant like if it were a seed to a sapling to a full grown tree. For plant growth states wouldn't be used since plants can't grow backwards and states can be changed in a non-linear way.

### Activity 4
Attendance: Gael Porras, Jeremiah Yang

Proposal: [Final Project Proposal First Draft](https://docs.google.com/document/d/1-4LVGJgfxqEb7zRdfGDfO5tOJxruOldH0SpWawnbftE/edit?tab=t.0#heading=h.wcm5jag04eng)

## Week 6 In Class Activity

### Activity 1
Notes:
- <<<<<<< HEAD shows the beginning of your code, ======== shows the split where the other's persons code will begin, and >>>>>> shows the end of the merge conflict lines. Visual Studio offers various solutions to your merge conflict and choosing one should lead to the alligator lines disappearing which means the merge conflict has been resolved. You can then push the resolved code so the rest of your teammates can work on the project. This will be especially helpful in our final project since merge conflicts seem inevitable with a lot of people working on the same project, and now we know how to resolve merge conflicts!
- The Profiler tool can be opened with window analysis profiler in Unity, then you can run the game until it begins getting laggy again and pause to inspect that specific laggy frame. The spikes in the chart should NOT be extremely high like in the demo since it means Unity is having intense issues rendering the game. The two most important columns will be the overview and time ms columns.
You can go deeper into the hierarchies to see what is making the system take so long rendering. Then you can find the specific issue (in this demo the badfruit had a lot of angles in its polygon collider which made Unity run a lot of calculations and lagged the game). A normal profiler should have peaks that don't go off the screen, barely rise, and are all the same instead of a single peak standing out. This tool will also be useful for our final project because it will help us identify lag spikes when playtesting our game and also help us prevent from making future lag spikes later on in our game's development.
- Gizmos can be useful when visually displaying things such as colliders, where you wouldn't need to click on every gameobject and instead make it appear on every gameobject at once within the scene. It's also good to make the color something you can visually see easily as Unity's default green is a little difficult to see. You can also add components to the gizmo as well, like in the demo you can add the fruit collider to see the size of the collider of both the fruit and capybara. Gizmos can also be used for things like velocity to see where the gameobject is moving to and how fast its moving. You can make the gizmo script so that you can attatch any component that is a circle collider or has a rigidbody to change what gameobjects have their components displayed or not. Gizmos would be extremely useful for our project because it allows us to visually see components and code within our scene while they would be completely invisible to the player or during playtesting.
- Breakpoints can be placed on a line of code to make the code stop at that specific line. By using run and debug after attaching to Unity, you can see your code run visually when you play the scene in Unity. The breakpoint also stops the program (or Unity) from running when it hits whatever line of code it is placed on. The Call Stack shows the methods that were called that led to the method you are currently now at. This allows you to find the issues within your code more easily, for example the issue in the demo was that the resetgame method was being called before the capybara singleton since the singleton uses Start while the resetgame method uses Awake. Breakpoints would be useful in our final project because it allows us to see the chain of events that led to the issue within a specific line of code and more easily fix it.

### Activity 2
Attendance: Gael Porras, Jeremiah Yang

[Final Project Proposal Final Draft](https://docs.google.com/document/d/1-4LVGJgfxqEb7zRdfGDfO5tOJxruOldH0SpWawnbftE/edit?tab=t.0)

## Week 7 In Class Activity

### Activity 1
Notes:
- Gizmo can show obstructions in an NPC's line of sight towards a player
- Gizmo also shows dot where obstruction is (like the dot on the tree since that is where the line of sight of the duck is obstructed)
- Finite State Machine is used on the duck (wandering state and pursue state) so if the player enters the duck's line of sight then the duck changes states
- States don't happen at the same time (mutually exclusive) and the duck can go back forth between these states (if the duck loses sight of the player then he goes back from pursue state to wandering state until the duck sees the player in their line of sight again)
- Update method is changing and using the state member variable
- Vectors are used to represent out position and movement within the game
- Raycast is used as the duck's line of sight (in the scene it is represented as the red line petruding from the duck)
- The red line/line of sight is being drawn by the gizmos code so it can only be seen in the scene
- using a player tag to check if the raycast hit the player allows for obstacles like trees to obstruct the line of sight of the duck
- Spherecast is like a raycast but instead of an arrow it is looking within an area using a sphere shape (this allows obstacles that wouldn't normally be seen by the duck, like a short table, to be seen by the spherecast)

### Activity 2
Attendance: Gael Porras, Jeremiah Yang

### Activity 3
![final project break down week 7 activity](https://github.com/user-attachments/assets/d6e95fb3-cb73-4156-aec8-f3bef1808ee4)


### Activity 4
[GDIM 32 Final Taskboard](https://docs.google.com/document/d/1qcCvx221nZpAMjmwJdpyKQ7kBxEmTlBFmETyLgA6mj8/edit?tab=t.0)

### Activity 5
[Added Simple Environment](https://github.com/1234321blue/GDIM32-Final/commit/fe22adbcc4a8ab870a05f8f296c25d29167e406c)
Here I simply added a very basic environment for our game, I plan on adding more detail later but for now this will serve as a baseplate for adding the NPC and player themsevles. That way, when we need to do some play testing we will be able to visualize how the game would look compared to testing on an empty plate in the void.