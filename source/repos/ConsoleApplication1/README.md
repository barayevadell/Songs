#  Songs Project

##  Overview
The **Songs** project is a C++ console application that implements a simple playlist manager.  
The program works only with **numeric song IDs** (integers).  
It was developed as an academic exercise to practice **Object-Oriented Programming (OOP)** and **linked lists**.

---
##  Features
The program supports the following commands:

0. **Print size** – shows the number of songs currently in the playlist.  
   - Input format: `0`

1. **Remove at index** – removes the song at a given index in the playlist.  
   - Input format: `1 <index>`

2. **Add song at the end** – adds a new song ID to the end of the playlist.  
   - Input format: `2 <songId>`

3. **Play all** – prints all songs in the playlist (by ID).  
   - Input format: `3`

4. **Swap adjacent** – swaps the song at the given index with the one immediately after it.  
   - Input format: `4 <index>`

5. **Add song at the beginning** – adds a new song ID to the beginning of the playlist.  
   - Input format: `5 <songId>`

6. **Clone playlist** – creates a duplicate of the current playlist (deep copy).  
   - Input format: `6`

7. **Exit** – terminates the program.  
   - Input format: `7`

---

## How to Build & Run
1. Clone the repository:
   ```bash
   git clone https://github.com/barayevadell/Songs.git
   ```
2. Open ConsoleApplication1.sln in Visual Studio 2022.
3. Build the project (Ctrl+Shift+B).
4. Run the program (Ctrl+F5).

---
##  Example Input & Output
```bash
Input: 
3
2
10
2
20
3

Output: 
10
20
```


---
##  Technologies

- C++

- Visual Studio 2022

- GitHub
