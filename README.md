# Plurality Voting Program

This program implements a simple plurality voting system, as introduced in the CS50 course.

## 📌 Description
The program allows users to input a list of candidates through command-line arguments. It then asks for the number of voters and allows each voter to cast a vote by entering a candidate’s name.

The candidate with the highest number of votes wins.  
In case of a tie, all candidates with the highest vote count are printed.

## 🛠 Features
- Accepts up to 9 candidates.
- Validates votes and handles invalid names.
- Supports multiple winners in case of ties.

## 🚀 How to Run
Compile:
make plurality

makefile
Copy code

Run:
./plurality Alice Bob Charlie

typescript
Copy code

Enter number of voters:
Number of voters: 3
Vote: Alice
Vote: Bob
Vote: Bob

makefile
Copy code

Output:
Bob

markdown
Copy code

## 📂 File Structure
- `plurality.c`: main C source code implementing the voting logic.

## 👨‍💻 Author
OMAR ALMUGHWISH   
