# NAPROCK Training Repository 

This repository stored the NAPROCK 2023 contest document, material, and software.

## Table of Contents

- [Contest Document](#Document)
- [Contest Server](#Server)

# Document
- The document outlines the overview, rules, demonstration booth setup, judging criteria, registration process, inquiry contacts and other details for participating in each contest section. It is an international contest hosted by NAPROCK and co-sponsored by institutions supporting programming contests in Japan's technical colleges.

Competition Section: This is a territorial game played between two teams, where craftsmen move around a rectangular board divided into areas, building and destroying walls to claim territories and castles for points. Details on the game rules, scoring, and technical specifications are provided.

This document is crucially important for  participants in this contest section:

- Understanding the game rules and mechanics is essential for participants to design and program their strategies for moving craftsmen, building/destroying walls, and claiming territories to score points.

- Knowing the specifics of the game field layout, time limits per turn, number of games/turns, scoring system, and winning conditions allows teams to develop AI algorithms and heuristics tailored for optimal gameplay.

- The technical specifications like data transmission protocols, field/action formats, and provided software libraries enable participants to properly integrate their programs with the contest system.

- Details on game state access and information flow during gameplay are vital for teams to extract relevant data and make informed decisions each turn.

- Logistics around booth setup requirements, computer specifications, power limits etc. help participants plan and test their systems for the on-site competition environment.

# Server
The "Server" folder contains sample server programs for the contest. Contest participants can start the server on a local network and test their own programs. Participants need to test technical aspects such as data transmission protocols, field/action formats, and information flow during gameplay.

- How to use [Windows]
1. Open File Explorer by pressing the Windows key + E.
2. Navigate to the location where the "Start server.bat" batch file.
3. Double-click on the batch file to execute it.

You can modify the batch file to select any JSON file from the same folder. Each JSON file contains a token to join the game and specifies which team you're on. The token for the first team is "0987," and for the second team, it's "1234."

- How to use [macOS]
To execute a .sh file in macOS, you can follow these steps:

1. Open the Terminal application. You can find it in the "Utilities" folder within the "Applications" folder, or you can use Spotlight search (Cmd + Space) and type "Terminal" to launch it.
2. Navigate to the directory where the .sh file is located. You can use the cd command followed by the path to the directory.
3. Ensure that the file has executable permissions. You can use the "chmod +x Start_server_mac.sh" command to add the executable permission if needed. 
4. Once you are in the correct directory, you can execute the "Start_server_mac.sh" file by typing "./Start_server_mac.sh" and press Enter to execute. The commands within the script will be executed sequentially.

