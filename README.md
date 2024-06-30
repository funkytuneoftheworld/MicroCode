# MicroCode BETA

MicroCode is a modern programming language designed for simplicity and efficiency.

## How to Run

### Prerequisites

- Ensure you have `g++` installed on your system. You can download it as part of [MinGW](http://www.mingw.org/).

### Steps to Run on Windows

1. **Clone the Repository**:
    ```sh
    git clone https://github.com/yourusername/MicroCodeBeta.git
    cd MicroCodeBeta
    ```

2. **Compile and Run the Program**:
    - Open Command Prompt and navigate to the directory where you cloned the repository:
      ```cmd
      cd C:\Users\crous\Downloads\MicroCodeBetaBuild0.0.1
      ```
    - Run the batch script with the desired command. For example, to spam "CARDINALS DA BEST BURD!" 100 times:
      ```cmd
      run_microcode.bat cardinal
      ```

## Commands

- **Run Script**:
    ```cmd
    run_microcode.bat run <script.mcs>
    ```
- **Compile Script**:
    ```cmd
    run_microcode.bat compile <script.mcs> -o <output.mci>
    ```
- **Convert to Source File**:
    ```cmd
    run_microcode.bat tosource "<code>" -o <output.mcs>
    ```
- **Convert to Intermediate File**:
    ```cmd
    run_microcode.bat tointermediate "<code>" -o <output.mci>
    ```
- **Spam Cardinal Message**:
    ```cmd
    run_microcode.bat cardinal
    ```
- **Admin Commands**:
    ```cmd
    run_microcode.bat admin
    ```

## Admin Commands

Running `run_microcode.bat admin` with administrator privileges will give you access to the following commands:

- **Reboot**: Reboots the system.
- **Shutdown**: Shuts down the system.
- **Clean**: Cleans temporary files.

### Example

To print "CARDINALS DA BEST BURD!" 100 times, run:
```cmd
run_microcode.bat cardinal
