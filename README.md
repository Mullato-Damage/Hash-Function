# Hash-Function
A program implementing a custom hash function with an interactive GUI.

## Project Description
This project demonstrates a custom hash function in Python, wrapped in a user-friendly GUI built with tkinter. The program allows users to hash inputs, view results, and save/load hashed outputs interactively. It showcases the principles of hashing, GUI design, and file handling, while also visualizing how hash tables resolve collisions.

## Features
**Hash Table and Hash Function**
- **Custom Hash Function**:
  - Combines input text with a "salt" value for randomness.
  - Computes the hash as the sum of Unicode values of all characters, modulo the table size.
  - Maps the hash to a specific index in the hash table.
- **Collision Handling**:
  - Uses chaining to store multiple key-value pairs at the same index when collisions occur.

**Interactive GUI**
   - Add your own inputs and view how they are hashed and stored in the table.
   - Predefined test cases run on startup to demonstrate functionality.
   - View debug information to understand how raw hash values and indices are computed.
   - Toggle between light mode and dark mode for visual comfort.

**JSON Integration**
  - Save the current state of the hash table to a JSON file.
  - Load hash table data from any JSON file to restore previously saved results.

## Requirements
- Python
- `tkinter` (included in the standard Python library)

## How to Run
1. Clone this repository.
2. Run the script:
   ```bash
   python main.py
3. Use the GUI to interact with the program.

## Example Outputs

Input  	      &nbsp; &nbsp; Hashed Index      	  &nbsp; &nbsp; Raw Hash

HowdyYall	    &nbsp; &nbsp; 0                   &nbsp; &nbsp; &nbsp; &nbsp; 1103

howdyyall	    &nbsp; &nbsp; 7                   &nbsp; &nbsp; &nbsp; &nbsp; 1107

😊🎉	         &nbsp; &nbsp; &nbsp; &nbsp; 8                  &nbsp; &nbsp; &nbsp; &nbsp; 8254

![image](https://github.com/user-attachments/assets/3e045645-3a4d-4005-9b66-7839586b6c2e)

## Features in Action
1. **Preloaded Test Cases**:
  - On startup, the hash table automatically loads predefined test cases and shows the current state of the table.
2. **Add Your Own Inputs**:
  - Interactively add inputs to the table and view how they’re stored.
3. **Save/Load Results**:
  - Save the current hash table to a JSON file and restore it later.

## Acknowledgments
This project reflects an effort to learn and apply 
- Hash functions and their integration with hash tables.
- Collision handling in hash tables using chaining.
- GUI design principles for creating an interactive experience.
- JSON integration for saving and loading data persistently.
