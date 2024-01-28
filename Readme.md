# Port Scanner

## Description
This Python script is a simple port scanner that scans a target IP address for open ports within a specified range. It utilizes the `socket` module to establish TCP connections to the target ports and determine their status (open or closed).

## Usage
To run the script, execute it from the command line and provide the target IP address as a command-line argument:

python3 scanner.py <ip>

Replace `<ip>` with the IP address of the target you want to scan.

## Functionality
1. **Target Specification:** You can specify the target IP address as a command-line argument when running the script.

2. **Scanning Range:** By default, the script scans ports from 50 to 84 (inclusive). You can modify this range by adjusting the values in the `range()` function within the `for` loop.

3. **Port Scan:** The script attempts to connect to each port in the specified range using TCP. If a connection is successful, it prints a message indicating that the port is open.

4. **Error Handling:** The script includes basic error handling for keyboard interrupts (`KeyboardInterrupt`), hostname resolution errors (`socket.gaierror`), and socket connection errors (`socket.error`).

## Example

python3 scanner.py 192.168.1.1

This command will scan ports 50 to 84 on the IP address `192.168.1.1` and print the status of each port (open or closed).

## Note
- This script is intended for educational purposes and should be used responsibly. Scanning networks or systems without proper authorization may violate ethical guidelines or legal regulations.
- Be mindful of network policies and obtain permission before scanning any network that you do not own or administer.
This command will scan ports 50 to 84 on the IP address `192.168.1.1` and print the status of each port (open or closed).

## Note
- This script is intended for educational purposes and should be used responsibly. Scanning networks or systems without proper authorization may violate ethical guidelines or legal regulations.
- Be mindful of network policies and obtain permission before scanning any network that you do not own or administer.

