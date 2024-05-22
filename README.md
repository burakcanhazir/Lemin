README
Project Title
Ant Colony Pathfinding

Project Description
This project is designed to simulate and validate the pathfinding of ants in a colony. The program reads from a file, validates its contents, and ensures the format is correct for simulating the ants' movements. It includes various checks to ensure the input data is correct and adheres to the specified format.

Features
File Type Check: Ensures the input file is a .txt file.
Comment Cleaning: Removes single line comments from the input.
Content Separation: Separates the content by lines.
Format Validation: Ensures the input adheres to the required format, including:
Correct number of ants
Presence of ##start and ##end points
No duplicated rooms
Valid coordinates for rooms
Correct room names
Valid links between rooms
Ensuring the end room is connected to the graph

Usage
Ensure the input file is a .txt file.
The input file should contain the number of ants, rooms, and links between the rooms in a specific format.
The program will validate the input file and provide appropriate error messages if any issues are found.