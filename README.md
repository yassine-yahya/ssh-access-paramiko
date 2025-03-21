🚀 SSH Connection Script (Python + Paramiko)
This script automates SSH connections using Paramiko and handles common SSH errors gracefully.

🔹 Features
✅ Connects to an SSH server using a hostname, username, and password
✅ Runs basic commands (e.g., whoami) after login
✅ Handles errors properly (wrong credentials, SSH disabled, timeout issues)
✅ Color-coded output using Colorama for better readability

🔹 Installation
First, install the required libraries:

bash
Copy
Edit
pip install paramiko colorama
🔹 Usage
Run the script and enter your hostname, username, and password when prompted:

bash
Copy
Edit
python ssh_access.py
Example input:

yaml
Copy
Edit
🔹 Hostname: test.rebex.net
🔹 Username: demo
🔹 Password: password
Example successful output:

css
Copy
Edit
🔄 [*] Connecting to test.rebex.net...
✅ [+] ***** Connected to test.rebex.net *****
🖥️ > whoami:
demo
🔌 [+] Connection closed.
🔹 Error Handling
This script provides clear error messages if something goes wrong:

Error	Message
Wrong password	❌ Authentication failed. Wrong username or password.
SSH disabled	🚫 Unable to connect. SSH might be disabled or port closed.
Timeout	⏳ Connection Timeout. SSH might be blocked.






🟢 Rebex Test SSH Server
✅ Host: test.rebex.net
✅ Username: demo
✅ Password: password
✅ Port: 22
✅ Supports: SSH & SFTP

🟢 Devzat SSH Chat Server (For Fun)
✅ Host: ssh.devzat.io
✅ Port: 22
✅ No password required!
