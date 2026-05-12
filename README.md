# Assignment 1: Sensor Data Logger

A C++ application designed to simulate sensor data collection, manage temporary buffers, and maintain execution logs. This project was updated to ensure cross-platform compatibility and a clean repository structure.

## 🚀 How to Run

### Prerequisites
Ensure you have a C++ compiler (like `g++`) installed on your system.

### Compilation
Open your terminal in the project root and run:
```bash
g++ src/program.cpp -o program
```

### Execution
Run the compiled binary:
```bash
./program
```

## 📁 Project Structure

- `src/`: Contains the source code (`program.cpp`).
- `output/`: The directory where all generated files are stored.
  - `sensor_data.txt`: The primary data log containing simulated units.
- `PROBLEMS.md`: Documentation of identified issues and their respective fixes.
- `.gitignore`: Configuration to prevent build artifacts and system-specific files from being tracked by Git.

## 🛠 Features

- **Data Simulation:** Generates 5 unique sensor readings using a randomized algorithm.
- **Directory Management:** Automatically ensures the `/output` directory exists before writing files.


Tuesday, 12th May, 11p.m.