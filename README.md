# Process Scheduling - Waiting Time and Turnaround Time Calculation

This is a C++ implementation of a scheduling algorithm that calculates the waiting time and turnaround time for a set of processes based on their burst times.

## Table of Contents

- [Overview](#overview)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Code Explanation](#code-explanation)
- [Contributing](#contributing)
- [License](#license)

## Overview

This program simulates the calculation of waiting time and turnaround time for a set of processes. It asks for the number of processes, their IDs, and their burst times, and then computes and displays the waiting time and turnaround time for each process, as well as the average waiting and turnaround times.

## Requirements

- A C++ compiler (e.g., g++)
- Standard C++ library

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/process-scheduling.git
   cd process-scheduling
###Code Explanation
The code is structured as follows:

Functions:

findWaitingTime: Calculates the waiting time for each process.
findTurnAroundTime: Calculates the turnaround time for each process.
findavgTime: Calls the above functions and computes the average waiting and turnaround times.
Main Function:

Prompts the user to input the number of processes, process IDs, and burst times.
Calls findavgTime to perform the calculations and display the results.

###Example Output
   ```bash

Enter the number of processes: 3
Enter the process ID for process 1: 1
Enter the burst time for process 1: 5
Enter the process ID for process 2: 2
Enter the burst time for process 2: 3
Enter the process ID for process 3: 3
Enter the burst time for process 3: 8

Processes  Burst time  Waiting time  Turn around time
 1          5          0             5
 2          3          5             8
 3          8          8             16

Average waiting time = 4.33333
Average turn around time = 9.66667

