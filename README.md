# Automated Network Reconnaissance Tool

This script automates basic network reconnaissance tasks using Nmap and Bash.

## Requirements
- Linux OS
- Nmap installed
  	```bash
  	pip install nmap
  	```
- Bash shell

## Usage
1. Clone the repo:
	```bash
	git clone https://github.com/Quinter-Jaika/Nmap-bash-scanner
	 ```
2. Navigate to the directory
	```bash
	cd nmap-bash-scanner
	```
3. Make it executable
	```bash
	chmod +x scan.sh
	```
4. Confirm a folder for results exists
	```bash
	mkdir -p results
	```
5.  Run the scanner
	```bash
	./scan.sh
	```
6. Enter a target IP or domain when prompted

## Example Scan Outputs
![Example Scan Output](scanme.nmap.org.png)

*Figure: Running the scan.sh script with target "scanme.nmap.org"*

![Example Scan Output](192.168.1.1.png)

*Figure: Running the scan.sh script with target "192.168.1.1"*

![Example Scan Output](127.0.0.1Part1.png)
![Example Scan Output](127.0.0.1Part2.png)

*Figure: Running the scan.sh script with target "scanme.nmap.org"*

The script performs:
- Ping scan
- Port scan
- OS & service detection and saves the full result in the 'results' folder
