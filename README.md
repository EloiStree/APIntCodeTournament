**Live DDNS**:   
[code-tournament-output.ddns.net](https://code-tournament-output.ddns.net) • [code-tournament-input.ddns.net](https://code-tournament-input.ddns.net)  
[apint.ddns.net](https://apint.ddns.net)• [apint-dev.ddns.net](https://apint-dev.ddns.net)    
_It’s just a POC/WIP right now—no DDoS protection yet, so please go easy on it._  

----------------

# APInt Code Tournament

> Learn code 💻 by playing in game tournaments 😛.  


**Offline vs realtime online**  

Execute code of random user is dangerous, that why I am going in an offline LAN tournament.  
But my aim is to make mixed of those.  


# Where to start ?
Five games to train on with Godot and [S2W](https://github.com/EloiStree/2024_08_29_ScratchToWarcraft)  


## Official tournament

### Online with Cryptography identification (or Twitch Play)

<img width="1258" height="736" alt="image" src="https://github.com/user-attachments/assets/003ef0cd-409f-4212-b645-4ffa70bc535e" />

### Offline code based in Python

<img width="973" height="717" alt="image" src="https://github.com/user-attachments/assets/dcb2096a-7ecd-4f63-ab6c-f5c40f0a6024" />

## WebGL Mini Games

_Learn by playing some game only by code without controller_  
<img width="1035" height="425" alt="image" src="https://github.com/user-attachments/assets/aa30600c-6cd1-4d16-bff6-9918998394c5" />  


---------------

# Context


My name is Eloi Stree and I want to have fun organising coding tournaments and teach for a living.   

I am going to organise two kinds of online tournaments:  
* Godot Engine Tournament: We create the game of the tournament.   
* Game Hack Tournament: We "hack" a game to propose only code speedruns.  

**Next Hacked Game:**
* 10 Second Ninja: Easy to learn

**Next Godot Game:**
* Artillery DOS XR: Because we need a Proof Of Concept that is easy to implement and can stand the test of time
* 10 Seconds Drone : Copy of the concept 10 Seconds Ninja, a workshop to learn how to use Godot with drone.
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


---------------


## How ?

As a single player offline  
<img width="1017" height="644" alt="image" src="https://github.com/user-attachments/assets/02dcc949-6ee6-4271-bd33-5fd58ba41857" />

As multiplayer online  
<img width="1071" height="642" alt="image" src="https://github.com/user-attachments/assets/1ba8bf7a-fa99-4bd6-99ad-b208c4314ae2" />

As multiplayer offline
<img width="1000" height="733" alt="image" src="https://github.com/user-attachments/assets/78003f00-4165-4b9a-a409-f2b6c9a6f2b5" />


Learn how to code with 10 Seconds Ninja and Pico2W
<img width="919" height="457" alt="image" src="https://github.com/user-attachments/assets/af644068-5ee2-4986-ac7f-b9ed4f5304d5" />

Learn how to code with Lifeoff and XInput ( ESP32S3 + Arduino )
<img width="1278" height="784" alt="image" src="https://github.com/user-attachments/assets/02246645-be00-4875-88a0-f332c2628adf" />

Learn how to code from BLE Gamepad on phone with ESP32S3
<img width="1058" height="690" alt="image" src="https://github.com/user-attachments/assets/6283c39c-08fd-4566-997f-3bc92bc6df2f" />

Learn to automate trash game with BLE and Webcam reading ( ESP32S3 + Webcam )
<img width="1048" height="686" alt="image" src="https://github.com/user-attachments/assets/499a3708-9142-4abd-9f5e-7635aee2fe55" />

Learn to control games from your XR headset
<img width="869" height="737" alt="image" src="https://github.com/user-attachments/assets/5e933152-4d78-426b-b5b0-64f84f8e30f1" />

Learn to finish the Death Mine in Wow on your private server
<img width="1310" height="681" alt="image" src="https://github.com/user-attachments/assets/604c3d9d-dfe9-4089-bdc6-552ad2f14443" />




----------

# Draft links

Current Mini Games beeing made in Godot:   
https://github.com/EloiStree/2025_11_20_CodeTournamentGodotMiniGames/tree/main  


To Do:
- Hack Games
  - https://github.com/EloiStree/APIntCodeTournamentGodotHackGames
    - https://github.com/EloiStree/APIntCodeTournamentHardwarePico2W
    - https://github.com/EloiStree/2024_08_29_ScratchToWarcraft
    - https://github.com/EloiStree/APIntCodeTournamentHardwareESP32S3/tree/main
      - https://github.com/EloiStree/2023_06_21_ArduinoToX360
      - https://github.com/EloiStree/2022_01_24_XOMI
- Mini Games
  - https://github.com/EloiStree/APIntCodeTournamentGodotMiniGames
    - https://github.com/EloiStree/APIntCodeTournamentPythonRelay

- Multiplayer
  - https://github.com/EloiStree/HelloPicoGodotMQTT


Unstore
- https://github.com/EloiStree/2025_10_27_gdp_lan_code_tournament_abstraction
- https://github.com/EloiStree/IID

Delete or Do:
- https://github.com/EloiStree/2026_01_01_PicoW_CodeTournamentClient
- https://github.com/EloiStree/2026_01_01_ESP32_CodeTournamentClient

Interact with wow:
- https://github.com/EloiStree/2025_07_23_WowAddonTextToColorTelemetry
Interact with Godot and Unity3D
- https://youtu.be/tiBhuXFUcpE
- https://youtu.be/1WNZ1vsFwXY?t=260

APInt Gate:
- https://github.com/EloiStree/2024_05_11_GateIID_WS_Python
- Send IID from Python https://github.com/EloiStree/2024_05_17_BasicPythonUdpWebsocketIID
- 


Open Macro Input:
- https://github.com/EloiStree/OpenMacroInput
  - MDI: https://github.com/EloiStree/2021_11_13_MidiToKeyboardActionDemo
    - https://github.com/EloiStree/2024_05_17_MidiToIIDPython

Old server APInt POC:
- https://github.com/EloiStree/2024_04_04_IndexIntegerDateTunnelingRSA
