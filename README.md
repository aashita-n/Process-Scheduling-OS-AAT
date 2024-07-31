
# Process Scheduling Algorithms

## Description

This project implements three fundamental CPU scheduling algorithms to manage process execution in an operating system. The algorithms included are:

1. **Round Robin Scheduling (RR)**: Allocates a fixed time slice (quantum) to each process in a cyclic order.
2. **Shortest Job First Scheduling (SJF)**: Selects the process with the shortest burst time for execution.
3. **Priority Scheduling**: Executes processes based on their priority levels.

The provided code demonstrates how these algorithms work and compares their results using sample processes with different burst times and priorities.

## Features

- **Round Robin Scheduling**: Handles time-sharing by rotating processes based on a specified quantum.
- **Shortest Job First Scheduling**: Prioritizes processes with the shortest execution time.
- **Priority Scheduling**: Executes processes based on predefined priority levels.

## Requirements

- Python 3.x

## Usage

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/process-scheduling-algorithms.git
    ```

2. Navigate to the project directory:
    ```bash
    cd process-scheduling-algorithms
    ```

3. Run the `main` function to execute the scheduling algorithms:
    ```bash
    python scheduling_algorithms.py
    ```

## Output

The program will display the results for each scheduling algorithm including:
- Process ID (PID)
- Burst Time
- Priority (for Priority Scheduling)
- Waiting Time
- Turnaround Time

### Example Output

```
Round Robin Scheduling:
PID     Burst Time     Priority    Waiting Time    Turnaround Time
1       10             3           8               18
2       5              1           0               5
3       8              2           5               13

Shortest Job First Scheduling:
PID     Burst Time     Priority    Waiting Time    Turnaround Time
2       5              1           0               5
3       8              2           5               13
1       10             3           13              23

Priority Scheduling:
PID     Burst Time     Priority    Waiting Time    Turnaround Time
2       5              1           0               5
3       8              2           5               13
1       10             3           13              23
```

## Code Explanation

- **Process Class**: Defines a process with attributes for process ID, burst time, priority, waiting time, and turnaround time.
- **Round Robin Function**: Implements the Round Robin scheduling algorithm.
- **SJF Function**: Implements the Shortest Job First scheduling algorithm.
- **Priority Scheduling Function**: Implements the Priority scheduling algorithm.
- **Print Results Function**: Displays the results in a tabular format.

## Contributing

Feel free to fork the repository and submit pull requests with improvements or additional features.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```

