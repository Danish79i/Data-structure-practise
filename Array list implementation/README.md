📌 Array List Implementation in C++
📖 Overview

This project implements a simple Array List class in C++ with basic operations such as:

Insertion at a specific position

Deletion by position or by value

Searching for an element

Clearing the entire list

Displaying the elements

The program is menu-driven and allows user interaction to perform operations on the list.

⚙️ Features

Insert → Add an element at a given position.

Display → Print all elements in the list.

Remove by position → Delete the element at a specific position.

Remove by value → Delete the first occurrence of a specific value.

Find → Search for an element and return its position.

Clear → Remove all elements from the list.

Exit → Quit the program.

🖥️ How It Works

The user first enters the size (capacity) of the list.

A menu is displayed to perform operations.

The program loops until the user chooses to exit.

▶️ Sample Run
Enter size of the list: 5

--- MENU ---
1. Insert
2. Display
3. Remove by position
4. Remove by value
5. Find
6. Clear list
0. Exit
Enter choice: 1
Enter value: 10
Enter position: 1

--- MENU ---
Enter choice: 1
Enter value: 20
Enter position: 2

--- MENU ---
Enter choice: 2
Elements in the list: 10 20

--- MENU ---
Enter choice: 5
Enter value: 10
Found at position: 1

--- MENU ---
Enter choice: 4
Enter value: 20
Value not found :

🛠️ Tech Used

Language: C++

Concepts: Classes, Dynamic Arrays (new/delete), Pointers, Menu-driven program

📂 File Structure
ArrayList/
│── main.cpp       # Source code (contains Array_list class and menu)
│── README.md      # Project documentation
