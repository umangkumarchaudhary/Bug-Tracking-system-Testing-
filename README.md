# Bug Tracking System

## Overview

This simple Bug Tracking System is a console-based application written in C. It provides basic functionality to file new bugs, change the status of existing bugs, and generate bug reports. The system allows users to create bug files with details such as bug type, priority, description, and status.

## Features

1. **File a New Bug:**
   - Capture user details, bug type, priority, description, and status.
   - Generate a unique bug ID and save bug information in a text file.

2. **Change the Status of a Bug:**
   - Update the status of an existing bug file.
   - Display available status options: "Not Yet Assigned," "In Process," "Fixed," and "Delivered."

3. **Get Bug Report:**
   - Retrieve and display the contents of a bug file for reporting purposes.
   - Users can input the filename to view bug details.

4. **Exit:**
   - Terminate the Bug Tracking System.

## Usage

1. **File a New Bug:**
   - Select option 1.
   - Provide user details and bug information as prompted.
   - Choose the status of the bug.

2. **Change the Status of a Bug:**
   - Select option 2.
   - Input the filename of the bug to be updated.
   - Choose the new status for the bug.

3. **Get Bug Report:**
   - Select option 3.
   - Enter the filename of the bug for which you want to generate a report.

4. **Exit:**
   - Select option 4 to exit the Bug Tracking System.

## How to Run

Compile the C program using your preferred compiler (e.g., gcc) and run the executable. Follow the on-screen instructions to navigate through the Bug Tracking System's functionalities.

```bash
gcc bug_tracking_system.c -o bug_tracker
./bug_tracker

## Notes

- This system uses simple text files for bug storage.
- Bug filenames are automatically generated based on user input.
- Ensure the C standard library is available on your system for successful compilation.

Feel free to contribute to enhancing the features and functionalities of this Bug Tracking System. If you encounter issues or have suggestions, please create an issue in the repository.

## Contribution

If you would like to contribute to the development of this Bug Tracking System:

1. Fork the repository.
2. Create a new branch for your feature or bug fix: `git checkout -b feature/new-feature`.
3. Commit your changes: `git commit -m 'Add new feature'`.
4. Push to the branch: `git push origin feature/new-feature`.
5. Create a pull request.

Your contributions are welcome, and together we can improve this Bug Tracking System for better functionality and usability.
