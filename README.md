# FIFO Page Replacement Algorithm

This program implements the FIFO (First-In-First-Out) page replacement algorithm in C++. It simulates a page replacement scenario where pages are loaded into frames based on their arrival order. If a frame needs to be replaced, the oldest page in the frame is removed.

## Features

- Calculates the number of page faults using the FIFO page replacement algorithm.
- Allows the user to input the number of pages, frame capacity, and the page reference string.

## Getting Started

### Prerequisites

- A C++ compiler (e.g., g++)

### Installation

1. Clone this repository or download the source code.
2. Navigate to the directory where the source code is located.

###Code Explanation
Code Explanation
The program reads the number of pages, the capacity of frames, and the page reference string from the user. It uses an unordered set to represent the set of current pages and a queue to store pages in a FIFO manner. It then simulates the FIFO page replacement algorithm, counting the number of page faults.

Function: pageFaults
Input: Array of page references, number of pages, capacity of frames.
Output: Number of page faults.
Complexity: O(n)
Main Function
Prompts the user for the number of pages and the capacity of frames.
Reads the page reference string from the user.
Calls the pageFaults function to calculate and print the number of page faults.

### Compilation

To compile the program, run the following command in your terminal:

  ```bash
  g++ -o fifo_page_replacement fifo_page_replacement.cpp

Example Usage
Enter the number of pages: 12
Enter the number of frames: 3
Enter the page reference string: 7 0 1 2 0 3 0 4 2 3 0 3 2
Page Faults: 9
