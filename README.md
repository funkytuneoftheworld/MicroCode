# MicroCode BETA

MicroCode is a modern programming language designed for simplicity and efficiency.

## How to Run

### Prerequisites

- Ensure you have `g++` installed on your system. You can download it as part of [MinGW](http://www.mingw.org/).

### Steps to Run on Windows

1. **Download the ZIP File**:
    - Go to the [releases](https://github.com/funkytuneoftheworld/MicroCodeBeta/releases) page on GitHub and download the latest release.

2. **Extract the ZIP File**:
    - Right-click the downloaded `.zip` file and select "Extract All...".
    - Choose a destination folder and click "Extract".

3. **Compile and Run the Program**:
    - Open Command Prompt.
    - Navigate to the extracted folder:
      ```cmd
      cd path\to\extracted\folder
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
