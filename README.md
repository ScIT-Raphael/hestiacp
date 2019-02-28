[Hestia Control Panel](https://www.hestiacp.com/)
==================================================

Disclaimer
----------------------------
**Hestia Control Panel is in active development and has been made available as a pre-release beta.**<br>
**Please use caution if you choose to use this software in a production environment.**

**WARNING: This is a modified fork of the original Hestia Control Panel project for development and personal use.**<br>
**If you are looking to use Hestia Control Panel on your own server, please install it from https://github.com/hestiacp/hestiacp/.**

What is Hestia Control Panel?
----------------------------
* An open source web server control panel with an easy-to-use interface.
* A lightweight alternative to cPanel, Plesk, etc.

What roles does Hestia Control Panel support?
----------------------------
* Web (Apache/NGINX) with PHP
* DNS (BIND)
* Mail (Dovecot/Exim) with virus and spam filtering (via ClamAV/SpamAssassin respectively)
* SQL (MariaDB or PostgreSQL)

System Requirements
----------------------------
* Ubuntu 16.04 LTS or Ubuntu 18.04 LTS
* **NOTE:** Hestia Control Panel must be installed on a clean operating system to ensure proper functionality.

How to install
----------------------------
Connect to your server via SSH as the root user:
```bash
ssh root@your.server
```
Download the installation script:
```bash
wget https://raw.githubusercontent.com/kristankenney/hestiacp/master/install/hst-install-ubuntu.sh
```
Run the script and follow the on-screen instructions:
```bash
bash hst-install-ubuntu.sh
```
To perform an unattended installation with the default options:
```bash
bash hst-install-ubuntu.sh -f -y no -e <email> -p <password> -s <hostname>
```
For additional installation options:
```bash
bash hst-install-ubuntu.sh -h
```

License
----------------------------
Hestia is licensed under [GPL v3](https://github.com/hestiacp/hestiacp/blob/master/LICENSE) license.

Donations
----------------------------
Hestia Control Panel is open source and completely free for all to use and enjoy!<br>If you would like to make a donation to help cover development and infrastructure costs, you may do so via PayPal.<br><br>Please see the Donations section at https://github.com/hestiacp/hestiacp/ for more information. 