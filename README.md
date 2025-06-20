
# Vulnerability Scanner

## Introduction
The Vulnerability Scanner is a practical tool designed for cybersecurity enthusiasts to identify open ports and potential vulnerabilities on a target system. Built with Python and Tkinter, this application offers a graphical user interface (GUI) to input a target IP address or domain name and a port range for scanning. It leverages the `socket` library for basic port scanning, providing a simple yet effective way to assess network security. This tool is ideal for educational purposes and initial security assessments.

## How to Run
1. **Install Python**: Download and install Python 3.x from [python.org](https://www.python.org/downloads/). During installation, check "Add Python to PATH" and verify with `python --version` or `python3 --version`.
2. **Install VS Code**: Download and install Visual Studio Code from [code.visualstudio.com](https://code.visualstudio.com/).
3. **Save the Code**: Copy the `vulnerability_scanner.py` code into a file named `vulnerability_scanner.py` in a project folder.
4. **Run the Script**: Open VS Code, go to `Terminal > New Terminal`, navigate to the project folder (e.g., `cd C:\Projects\Scanner` on Windows or `cd ~/Projects/Scanner` on macOS/Linux), and type `python vulnerability_scanner.py` or `python3 vulnerability_scanner.py`, then press Enter. A GUI window will appear.
5. **Usage Example**:
   - **Target**: Enter a target IP or domain, e.g., `scanme.nmap.org` (a public test server by Nmap).
   - **Port Range**: Choose a port range, e.g., `1-100` to scan common ports including HTTP (port 80).
   - **Action**: Click the "Scan" button. The scan may take a few minutes depending on the range and network response. Results will display in the text area, e.g., "Port 80 is open (May indicate vulnerability, further analysis recommended)" for `scanme.nmap.org`.
6. **Note**: Select a reasonable port range (e.g., 1-1024 for common ports) and be patient as scanning large ranges or slow networks may take time. Ensure you have network permissions for the target.

## Conclusion
This Vulnerability Scanner provides a foundational tool for understanding network security by detecting open ports. While it offers basic functionality, it can be extended with libraries like `python-nmap` for advanced scans. It serves as an excellent starting point for learning cybersecurity practices and can be customized for more detailed vulnerability assessments in the future.

Contact: pawankumar73380@gmail.com  
LinkedIn: pavankumar022  

ThankYou
