# TapAway

## Authors
**Ahsen Doner, Iris Lin**

## Introduction
The game we have implemented is influenced by the mobile game *Tap Away*. The objective is to clear the screen by selecting boxes, which move in the direction of their arrows once selected. If the selected box is blocked by another box, it will move until it reaches the blocking box. This game was made in C and developed using Altera De1-Soc board.

## Game Operation

![image](https://github.com/user-attachments/assets/3e0ad096-d476-4760-97a6-5bd0760e488e)

The game starts with a start screen. When *Enter* is pressed on the PS2 keyboard, the user can begin playing.

![image](https://github.com/user-attachments/assets/a4fbc368-1ce5-4153-bf57-0c25fd6e34b3)

The player can move the red selection box using the **W, S, A, D** keys (up, down, left, right). The red box is used for selecting a box, and by pressing *Space*, the selected box will start moving in the direction indicated by its arrow.

![image](https://github.com/user-attachments/assets/e09575e3-6df5-4f11-83cd-90f2de53e4eb)

By pressing *Space*, the selected box moves in the direction of its arrow and disappears once it reaches the end of the screen. The objective is to clear all boxes from the screen.

![image](https://github.com/user-attachments/assets/935cb999-a369-4d49-ac3b-a69740a409bb)

If a selected box moves in a direction where it is blocked before reaching the end, a collision detection system stops the movement.

![image](https://github.com/user-attachments/assets/abbe861c-c4d5-4913-94a1-5cdef09feafc)

The *Q* key allows the player to rotate the boxes clockwise.

![image](https://github.com/user-attachments/assets/9a99f97d-f548-42b1-bdce-3bb6a147438c)

The HEX display is used to show the player's score, which corresponds to the number of cleared boxes.

![image](https://github.com/user-attachments/assets/47e40d71-3398-4a2a-9542-93f35e874dd2)

When the player successfully clears all the boxes, an audio cheer plays and an end screen is displayed.

![image](https://github.com/user-attachments/assets/20706590-dc01-4088-a70c-bbcf3092bdf0)

By pressing *Enter*, a new level is randomly generated with different block arrangements.

## Challenges
Implementing the game in **3D** was challenging since the logic needed to account for 3D and we needed to add the rotation feature to rotate 3D cubes.
We were able to implement the 3D game by taking small but frequent steps, such as first implementing the game in 2D, and developing the logic accordingly, and enhancing the game into 3D later on.
![CPULator output of the 3D visual.](path/to/3d_output.png)


