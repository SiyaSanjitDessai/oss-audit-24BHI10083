# oss-audit-24BHI10083
# Open Source Audit Project

## Student Details
- **Name:** Siya Sanjit Sawant Dessai
- **Registration Number:** 24BHI10083
- **Course:** Open Source Software
- **Chosen Software:** Linux Kernel

## Project Description
This project is an audit of the Linux Kernel as part of the Open Source Software course. It covers the origin, license, Linux footpnd ecosystem of the Linux Kernel. Five shell scripts are included to demonstrate practical Linux skills.

## Scripts Description

### Script 1: System Identity Report
Disps system information including distro, kernel version, user, home directory, uptime, date and time, and the GPL v2 license.

### Script 2: FOSS Package Inspector
Chewhether a package is installed on the system and prints a philosophy note about it using a case [statement.

### Script 3: Disk and Permission Auditor
Loops through key system directories and reports their permissions, ownership, and disk usage.

### Script 4: Log File Analyzer
Reads a log file, counts how many lines contain a keyword, and prints the last 5 matching lines.

### Script 5: Open Source Manifesto Generator
Asks the user three questions interactively and generates a personalised open source philosophy statementaved to a .txt file.

## How to Run Scripts

### Requirements
- Linux (Ubuntu / WSL)
- Bash shell

### Steps
1. Clone the repository:
   git clone https://github.com/SiyaSanjitDessai/oss-audit-24BHI10083
   cd oss-audit-24BHI10083

3. Give execute permission to all scripts:
   chmod +x script*.sh

4. Run Script 1:
   ./script1_system_identity.sh

5. Run Script 2:S
   ./script2_package_inspector.sh

6. Run Script 3:
   ./script3_disk_permission_auditor.sh

7. Run Script 4 (provide a log file path):
   ./script4_log_analyzer.sh /var/log/syslog error

8. Run Script 5:
   ./script5_manifesto_generator.sh

## Dependencies
- bash
- coreutils (ls, du, df, date, whoami)
- grep, awk, cut
- rpm or dpkg (for Script 2)
