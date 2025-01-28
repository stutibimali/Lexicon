# Word Bank Program

Welcome to the **Word Bank** program! This program implements a binary search tree (BST) to store and manage a dictionary of words, each with two associated meanings. It provides functionality for inserting, deleting, searching, and displaying words and their meanings. This program is written in C and can be a useful reference or starting point for learning data structures and algorithm implementations in C.

---

## Features

1. **Insertion**: Add a word with two meanings to the dictionary.
2. **Deletion**: Remove a word and its meanings from the dictionary.
3. **Search**: Find a word in the dictionary and display its meanings.
4. **Display**: View all words in the dictionary in alphabetical order (in-order traversal).
5. **Exit**: Close the program gracefully.

---

## Data Structure

The dictionary is implemented as a **binary search tree (BST)**, where:
- Each node contains:
  - `word`: The word (string).
  - `meaning1` and `meaning2`: Two meanings associated with the word.
  - Pointers to the left and right child nodes.
- The BST ensures that:
  - Words are sorted alphabetically.
  - Insertions, deletions, and searches are efficient.

---

## Code Overview

### Files and Functions

1. **Struct Definition**
   - The `struct tree` defines a BST node with fields for the word, meanings, and left and right child pointers.

2. **Core Functions**
   - `create`: Allocates and initializes a new BST node.
   - `insert`: Adds a new word and its meanings to the BST.
   - `del`: Deletes a word from the BST.
   - `search`: Searches for a word and displays its meanings if found.
   - `display`: Displays all the words in alphabetical order (in-order traversal).

3. **Utility Functions**
   - `pause`: Introduces a small delay for user interaction.

4. **Main Menu**
   - The main menu provides an interactive interface for users to access all features.

---

## How to Run

1. **Prerequisites**
   - A C compiler (e.g., GCC).
   - Basic knowledge of how to run a C program.

2. **Steps**
   - Clone the repository:
     ```bash
     git clone https://github.com/your-username/word-bank.git
     cd word-bank
     ```
   - Compile the code:
     ```bash
     gcc word_bank.c -o word_bank
     ```
   - Run the program:
     ```bash
     ./word_bank
     ```

3. **Usage**
   - Follow the on-screen instructions to insert, delete, search, or display words.

---

## Example Interaction

```
WELCOME TO WORD BANK OF YOUR OWN
        FOR
  RECOGNIZING SOMETHING NEW

1. Insertion     2. Deletion
3. Searching     4. Display
5. Exit
Enter your choice:
```

- Inserting a word:
  ```
  Word to insert:
  apple
  One word meaning:
  fruit
  One word meaning:
  tech
  ```

- Searching for a word:
  ```
  Enter the search word:
  apple
  word       : apple
  meaning    : fruit
  meaning    : tech
  ```

- Deleting a word:
  ```
  Enter the word to delete:
  apple
  WORD FOUND READY TO GET DELETED#!#
  W_O_R_D D_E_L_E_T_E_D !!
  ```

- Displaying the dictionary:
  ```
  word       : apple
  meaning    : fruit
  meaning    : tech
  ```

---

## Limitations

1. No file I/O for data persistence (words and meanings are lost when the program exits).
2. Limited input validation.
3. The `pause` function is a simple delay, which may not work uniformly across systems.

---

## Future Improvements

1. Add file handling to save and load the dictionary.
2. Improve input validation and error handling.
3. Enhance the UI for a better user experience.
4. Optimize the `del` function for edge cases.

---

## License

This project is licensed under the MIT License. Feel free to use and modify it.

---

## Contribution

Contributions are welcome! Open an issue or submit a pull request with improvements.

---

### Author

- **Stuti Bimali**  
  Feel free to reach out with questions or suggestions!
