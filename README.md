# Digital Logic Design (DLD) Simulation

## Overview
This repository contains simulations and experiments related to Digital Logic Design (DLD). These experiments help understand fundamental digital circuits and their behavior using simulation tools like Logisim, Quartus, or Verilog.

## Required Software

### Logisim
Logisim is a free and open-source logic circuit simulator used for designing and testing digital circuits.

#### Installation on macOS

##### Step 1: Download Logisim
1. Visit the [Logisim Official Website](http://www.cburch.com/logisim/) and download the `.jar` file.
2. Save the file in a convenient location, such as the `Downloads` folder.

##### Step 2: Install Java (if not installed)
1. Logisim requires Java to run. Check if Java is installed by running:
   ```sh
   java -version
   ```
2. If Java is not installed, install it using Homebrew:
   ```sh
   brew install openjdk
   ```

##### Step 3: Run Logisim
1. Open the terminal.
2. Navigate to the folder where the Logisim `.jar` file is saved. For example:
   ```sh
   cd ~/Downloads
   ```
3. Run Logisim using the following command:
   ```sh
   java -jar logisim.jar
   ```

#### Installation on Windows

##### Step 1: Download Logisim
1. Visit the [Logisim Official Website](http://www.cburch.com/logisim/) and download the `.jar` file.
2. Save the file in a convenient location, such as `Downloads`.

##### Step 2: Install Java (if not installed)
1. Check if Java is installed by running the following command in Command Prompt:
   ```sh
   java -version
   ```
2. If Java is not installed, download and install Java from the [Oracle JDK Website](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html) or use OpenJDK.

##### Step 3: Run Logisim
1. Open Command Prompt (`cmd`).
2. Navigate to the folder where the Logisim `.jar` file is saved. For example:
   ```sh
   cd C:\Users\YourUsername\Downloads
   ```
3. Run Logisim using the following command:
   ```sh
   java -jar logisim.jar
   ```

## Experiments

### Experiment 1
- Basic logic gates and their truth tables.

### Experiment 2
- Implementation of Boolean expressions using logic gates.

### Experiment 3
- Design and simulation of combinational circuits.

### Experiment 6: Adders & Subtractors
- **Half Adder** – Adds two binary digits and outputs sum and carry.
- **Full Adder** – Adds three binary digits (two inputs + carry-in) and outputs sum and carry.
- **Half Subtractor** – Computes the difference between two binary digits and outputs difference and borrow.
- **Full Subtractor** – Computes the difference of three binary digits (two inputs + borrow-in) and outputs difference and borrow.

### Experiment 7: Advanced Circuits
- **4-bit Full Adder** – A cascade of full adders to perform addition on 4-bit binary numbers.
- **BCD Converter** – Converts binary numbers to Binary Coded Decimal (BCD) format.
- **Comparator** – Compares two binary numbers and determines equality, greater than, or less than conditions.
- **Parity Checker** – Checks for even or odd parity in a given binary sequence.

## Running Simulations
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/DLD-Simulation.git
   ```
2. Open the relevant simulation files in your preferred tool (e.g., Logisim, Quartus, Verilog, etc.).
3. Run the simulations and analyze circuit behavior.

## Contribution Guidelines

- Label and document circuits clearly for better readability.
- Optimize circuit designs to enhance performance and efficiency.
- Maintain consistency in naming conventions and design structures.
- Fork the repository, make necessary improvements, and submit a pull request with detailed descriptions of changes.

## License
This project is open-source and available under the [MIT License](LICENSE).

