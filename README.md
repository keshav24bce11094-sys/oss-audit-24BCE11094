# oss-audit-24BCE11094
Open Source Audit Project
Student Details
Name: Keshav Gupta
Roll Number: 24BCE11094
Course: Open Source Software
Chosen Software: Pyhton

Python

Python is an open-source programming language known for its simplicity, readability, and wide range of applications such as web development, machine learning, data science, and automation.

Project Overview

This project focuses on analyzing Python as an open-source software. It includes both theoretical and practical components:

Study of origin and philosophy of Python
Analysis of its open-source license
Understanding its role in Linux systems
Exploring the open-source ecosystem
Comparison with proprietary software
Implementation of shell scripts demonstrating Linux concepts


Shell Scripts Description
Script 1 — System Identity Report
This script displays basic system information such as kernel version, current user, system uptime, date, and Linux distribution.

Script 2 — FOSS Package Inspector
This script checks whether Python is installed on the system and displays its details along with a short description using a case statement.

Script 3 — Disk and Permission Auditor
This script analyzes important system directories and displays their size, permissions, owner, and group information.

Script 4 — Log File Analyzer
This script reads a log file, counts occurrences of a keyword (default: "error"), and displays the last matching lines.

Script 5 — Open Source Manifesto Generator
This script takes user input and generates a personalized open-source manifesto, which is saved as a text file.

Step-by-Step Instructions to Run Scripts
Step 1: Open Terminal

Navigate to the project directory:
cd oss-audit-24BCE11094

Step 2: Give Execution Permission

chmod +x script1.sh
chmod +x script2.sh
chmod +x script3.sh
chmod +x script4.sh
chmod +x script5.sh

Step 3: Run Scripts

Run Script 1:
./script1.sh

Run Script 2:
./script2.sh

Run Script 3:
./script3.sh

Run Script 4:
./script4.sh /var/log/syslog error

Run Script 5:
./script5.sh

Dependencies
Linux Operating System (Ubuntu recommended)
Bash Shell
dpkg (for package checking)
Standard Linux utilities (grep, awk, du, ls, cut)

Key Learning Outcomes
Understanding open-source philosophy
Learning Linux file system and commands
Writing and executing shell scripts
Applying concepts like loops, conditions, and file handling
Understanding real-world applications of open-source software

Conclusion
This project helped in understanding both theoretical and practical aspects of open-source software. Python was analyzed as a powerful and flexible open-source tool. The shell scripts provided hands-on experience with Linux and automation concepts.
