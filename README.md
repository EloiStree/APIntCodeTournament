
# APInt Code Tournament

> Learn code 💻 by playing in game tournaments 😛.  

My name is Eloi Stree and I want to have fun organising coding tournaments and teach for a living.   

I am going to organise two kinds of online tournaments:  
* Godot Engine Tournament: We create the game of the tournament.   
* Game Hack Tournament: We "hack" a game to propose only code speedruns.  

**Next Hacked Game:**
* 10 Second Ninja: Easy to learn

**Next Godot Game:**
* Artillery DOS XR: Because we need a Proof Of Concept that is easy to implement and can stand the test of time
* Global Game Jam: Mystery box

**For a living:**

Outside of my simple curiosity:    
<img width="600" height="599" alt="image" src="https://github.com/user-attachments/assets/df6f7c7b-f533-4af6-94a5-30748d019193" />  
I am a freelance teacher through [SMArtBe](https://smartbe.be/en/), and this project is designed to teach in classrooms 😋.   
I can't wait for the project to be ready enough to be used in an auditorium or in a cinema.  

**Basic Mechanic:**

The concept is "simple":
Your code is dropped on a Pico 2W in CircuitPython, isolated on the network.

* It receives UDP text and bytes as the context of the current game state.
  * You need to read the manual of the game to know how to use them.
* Your code must send keyboard and gamepad input in this [S2W format](https://github.com/EloiStree/2024_08_29_ScratchToWarcraft).
  * If it is a Godot game, your input is simulated as a player to make an MMO-style contest.
  * If it is a hack tournament, your input is converted into real input on the device.

To publish your code, you need to hash and sign it with ECC or RSA.
The idea here is that it allows us to identify in whose name you are playing in the tournament.

I am a teacher and we are here to learn.
All those words 🤪 are going to become videos to teach you what they mean.
That is the point of this exercise.

**Contact Me:**
Hope you have fun with us in this project.
Feel free to ping me on the Eloi Teaching Discord:
[https://discord.gg/pvRjyNQEDp](https://discord.gg/pvRjyNQEDp)


**Offline vs realtime online**  

Execute code of random user is dangerous, that why I am going in an offline LAN tournament.  
But my aim is to make mixed of those.  

