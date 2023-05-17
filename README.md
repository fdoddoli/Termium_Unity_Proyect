# Introduction

Implemented a gamified web application for Terminum to train scrap inspectors. Embed in the web app is a "subway surfer like" game, built on unity, that allows scrap to train classifying scrap. In addition to play the game, users can take gamified tests and earn points based on their results. Inside their profile page, users can view the history of their test scores and the amount of points and medals achieved. 

<img width="459" alt="Screen Shot 2023-05-16 at 10 40 38 PM" src="https://github.com/fdoddoli/Ternium_Unity_Proyect/assets/58672371/4aeca4f3-ff9a-4e45-ba3a-9565af8242d2">

# App Demonstration 

https://drive.google.com/file/d/1eqx6Lu0RRO5piTgc-3fwc9IPwpDuWg4W/view?usp=sharing

# Game Description

The game has two modes: an exam and a practice. The objective of the exam mode is to answer a fixed number of questions assigned by an administrator. The objective of the practice mode is to sort as many photographs as possible according to the type of scrap they depict. The setting is a dungeon with three different tunnels, each representing a scrap type option.

The exam consists of a set number of questions determined by an administrator. The player has 3 lives, which are lost for each incorrect answer. The game mechanics are as follows: When a question starts, a photograph of the scrap to be analyzed appears. It is displayed for a limited time, indicated by the orange bar at the top of the screen. After the observation time ends, the player starts moving in the 'y' direction. The player has no control over this, only lateral movement control (x-axis) using the arrow keys. Above each of the three tunnels, a statement with scrap categories will appear. Only one statement will be correct. The player must move horizontally to the correct lane to enter the tunnel corresponding to the scrap category. If the player enters the correct tunnel, they move on to the next question following the same dynamics, and their vertical speed (y-axis) increases. This means they will have less time to choose the correct tunnel. If the player loses all three lives, the game ends, and they are assigned a score based on their performance in the exam. If they complete all 10 questions, the score will be recorded, and if it's one of the top 7 scores among all the inspectors, it will be on the leaderboard.

The mechanics of the practice mode are quite similar. The player receives a photograph with scrap, and once the observation time is over, the character starts running towards the tunnels, and the player has to choose the correct tunnel using the arrow keys. Unlike the exam, the practice mode has an unlimited number of lives and questions. Another difference is that in the practice mode, the player can see their character's speed in km/h. It increases as they enter the correct tunnels and decreases as they enter the incorrect ones.

# Game Preview
<img width="561" alt="Screen Shot 2023-05-16 at 10 41 33 PM" src="https://github.com/fdoddoli/Ternium_Unity_Proyect/assets/58672371/e27f302e-7ea9-451b-b23d-f5124db3aa8e">

<img width="562" alt="Screen Shot 2023-05-16 at 10 41 02 PM" src="https://github.com/fdoddoli/Ternium_Unity_Proyect/assets/58672371/4a90b9b2-33c6-46e6-8639-8658bb3ec5d4">


**Note**
Code is not included due to an NDA requirement from Termium. 
