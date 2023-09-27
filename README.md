# fail2ban-banlist
Fail2Ban Banned IPs List Script

Overview
This repository contains a Bash script that lists banned IPs along with the jails they are banned in on systems using Fail2Ban. Created by mjohn50n.

Features
Lists all Fail2Ban jails.
Displays banned IPs for each jail.
Provides a summary of banned IPs and their associated jails.
Requirements
A system running Fail2Ban
Administrative (sudo) access
Installation

1. Clone the repository: git clone https://github.com/mjohn50n/fail2ban-banned-ips-list.git
2. Navigate to the repository folder: cd fail2ban-banned-ips-list
3. Make the script executable: chmod +x list_banned_ips.sh

Usage
Run the script with administrative privileges: sudo ./list_banned_ips.sh

The script will list all banned IPs along with the jails they are associated with.

Contributing
Feel free to fork the repository and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

License
This project is licensed under the MIT License
