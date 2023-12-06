# LSforWindows

This project provides a batch file for Windows Command Prompt (CMD) that emulates the Unix `ls` command. It's a simple solution for those who frequently switch between Unix/Linux and Windows environments and find themselves typing `ls` out of habit in CMD.

## Installation

To install the `ls` command emulator:

1. **Clone or Download the Repository**:
   - Use `git clone` or download the ZIP from the GitHub repository.

2. **Copy the Batch File to System32**:
   - Copy the `ls.bat` file to your System32 directory to make the `ls` command available globally in CMD.
   - Note: This step requires administrative privileges.
   - Example command (run in Command Prompt as administrator):
     ```
     copy ls.bat C:\Windows\System32
     ```

## Usage

Once installed, you can use the `ls` command in CMD just like in Unix/Linux. It's particularly useful for those accustomed to Unix-like environments, reducing the minor but frequent inconvenience of typing `ls` in Windows.

## Background

This script was created out of the necessity to bridge habitual use of Unix commands while working in Windows Command Prompt, particularly for the common `ls` command.

## Contributing

Feel free to fork the repository, make improvements, or suggest changes. Contributions are always welcome!

