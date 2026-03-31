Open Source Audit Project — Git

Student Details

Name: Aditya Kumar Sharma

Registration Number: 24BCE10473
________________________________________
Project Overview

This project is a part of the Open Source Software course. The goal is to study an open-source tool (Git) and understand its technical and philosophical aspects.
Along with the report, five shell scripts are created to demonstrate practical Linux skills such as system inspection, package management, file analysis, and automation.
________________________________________
Chosen Software

Git — Distributed Version Control System

Git is used to track changes in code and enables collaboration among developers without relying on a central server.
________________________________________
System Requirements

Before running this project, ensure the following:

•	Linux-based system (Ubuntu preferred)

•	Bash shell (default in Linux)

•	Git installed

•	Basic terminal access
________________________________________
Environment Setup

Step 1: Update System Packages

Open terminal and run:

sudo apt update
________________________________________
Step 2: Install Git (if not already installed)

sudo apt install git -y

To verify installation:

git --version
________________________________________
Step 3: Download the Project

Clone the repository:
git clone : https://github.com/aditya-sharma381/OSS-Audit-24BCE10473.git

Move into the project directory:

cd OSS-Audit-24BCE10473
________________________________________
Step 4: Give Execution Permission to Scripts

chmod +x *.sh
________________________________________
Running the Scripts

Each script can be executed using the following format:

./script_name.sh
________________________________________
Script Details and Execution

1. System Identity Report
   
Displays system information such as kernel version, OS, uptime, and user.

./shell_script_1.sh
________________________________________
2. FOSS Package Inspector
   
Checks whether Git is installed and displays version and description.

./shell_script_2.sh
________________________________________
3. Disk and Permission Auditor
   
Analyzes key system directories and prints size, ownership, and permissions.

./shell_script_3.sh
________________________________________
4. Log File Analyzer
   
Counts occurrences of a keyword (default: "error") in a log file.

./ shell_script_4.sh
________________________________________
5. Open Source Manifesto Generator
   
Generates a personalized open-source statement based on user input.

./ shell_script_5.sh
________________________________________
Configuration Notes

•	Script 2 uses apt (Debian/Ubuntu systems).

•	If using Fedora/CentOS, replace with rpm commands.

•	Script 4 requires access to system log files (may need sudo).
________________________________________
Dependencies

•	Bash shell

•	Core Linux utilities:

o	grep

o	awk

o	du

o	ls

o	uptime

o	whoami

(All are pre-installed on most Linux systems.)
________________________________________
Expected Output

Each script prints structured output directly in the terminal.

Example outputs include:

•	System details (kernel, user, uptime)

•	Package information (version, description)

•	Directory permissions and sizes

•	Log keyword analysis results

•	Generated manifesto text file

________________________________________
Notes

•	All scripts are tested on Ubuntu Linux.

•	No external libraries are required.

•	Scripts are designed to be simple, readable, and easy to modify.
________________________________________
Conclusion

This project helped in understanding how open-source tools like Git operate both technically and philosophically. It also provided hands-on experience with Linux shell scripting and system-level automation.
