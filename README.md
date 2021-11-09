Using Assignment 1 / miderm quiz as a base.

Designed the platformer level to be a beginner type stage. The enmies arent meant to kill the player but just act as a small obstacle to get in the player's way. They are there to teachthe player that they reset their jump state, so that you can use them to jump off of them to reach higher heights.

The controls are WASD and SPACE to jump, To complete the level you make your way to the top of the level and enter a door.

Sources for where I learned how to code sections:

https://www.youtube.com/watch?v=dwcT-Dch0bA&ab_channel=Brackeys https://www.youtube.com/watch?v=eWBDuEWUOwc&ab_channel=Zyger https://www.codegrepper.com/code-examples/csharp/2d+movement+unity https://www.maxester.com/blog/2020/02/24/how-do-you-make-the-camera-follow-the-player-in-unity-3d/ https://answers.unity.com/questions/274809/how-to-make-enemy-chase-player-basic-ai.html https://www.youtube.com/watch?v=rhoQd6IAtDo&ab_channel=Blackthornprod https://docs.unity3d.com/Manual/Overview2D.html https://answers.unity.com/questions/1369393/how-to-switch-between-scenes.html https://docs.unity3d.com/ScriptReference/MonoBehaviour.OnCollisionEnter2D.html https://www.youtube.com/watch?v=PXqNGEkHHEk&ab_channel=OXMONDTutorials https://docs.unity3d.com/ScriptReference/Application.Quit.html https://gamedevbeginner.com/how-to-quit-the-game-in-unity/ https://www.tutorialspoint.com/unity/unity_the_button.htm

//New references
https://docs.unity3d.com/ScriptReference/Vector3.Distance.html?_ga=2.28400188.165380541.1636072851-209090507.1606616110
https://forum.unity.com/threads/how-do-i-get-the-distance-between-two-gameobjects.77331/

All sprites, Tiles, Assets, etc. Were made by me.

Audio Tutorials I used: 
https://docs.unity3d.com/ScriptReference/AudioSource.Play.html
https://docs.unity3d.com/ScriptReference/AudioSource-clip.html
https://www.youtube.com/watch?v=8pFlnyfRfRc&ab_channel=AlexanderZotov

Music is made by me. Sound effects created using:
https://sfxr.me/

Synthfont, Sforzando, Touhou.sf2 were used for music.

Youtube Video Link: https://youtu.be/TECZIHBrVMY

Goal is to make 2 DLLs, one that changes nothing, the other changing jump and movement speed.

DLL implementation is learnt and used from Laboratory 3 in Game Engines Design Class

NEW CONTENT (2021/11/04):
Added an enemy awareness range variable. If the player is outside that range, the enemys will not move, or update the player distance variable. 
I used the dirty flag optimization pattern to achieve this. Usually you would use this to save a game state to a text file, to then load and play at a later time, 
but considering saving and loading is out of my current skill set, i settled to just make it so that the enemies arent always running in the background, no matter how far they are from the player. This would help in cpu performance in larger levels. The DLL has compatibility with the new awareness variable. 

In addition, I added 3 simple tutorial playgrounds, 1 for movement, 1 for jumping, and 1 just so the player can see how the enemy behaves. All the tutorial sprites were created 
by me. New music was changed to something I made, its called Pioneers of Uncharted Dreams. I wouldve liked to replace the placeholder background, but making
a pixel art bacground takes a long time. Hence the music doesnt really fit. 

Optimization patterns were learned from Game Engines lab 7
