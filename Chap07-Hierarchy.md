#  Hierarchy

The Hierarchy section in Unity is where all the Game objects(cameras, sprites, managers(UI, Audio, etc.), lights) used in the scene are listed.

Hierarchy makes it easy for organizing game objects or club them together in a parent object. It is also easy for removing and adding game objects from Hierarchy rather than the Scene view.

You can make an object a child of another object by dragging one object to another. The dragged GameObject will become the child. The child object's position now can be changed relative to the parent. The local position is the position relative to the parent and the global position is basically the position in world space.

![Hierarchy](./Images/hie.png)

 Let's walk you through a quick exercise for this. There won't be any image resources for this so you have to try this to understand 😈

 Create another cube in your hierarchy.
 Put it at some random position.
 Select it and see the position in the inspector. This is your global position.
 Now drag it into the cube that you had already created.
 Observe the position in the inspector change. This is your local position
 Also try rotating, moving and scaling the parent cube.

Good Job! The same concepts will carry over to local rotations and local scale. You also learned how to follow instructions without a lot of explicit instructions.

![Thank me later!](https://media.giphy.com/media/txyLmYjGTRxj8RISaB/giphy.gif)
 
Interesting right? You guys can already imagine setting up some game mechanics using the hierarchy.

Ok quit playing, we still got stuff to do!



