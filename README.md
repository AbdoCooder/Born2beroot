# Born2beRoot 🛠️

## Overview 📚
**Born2beRoot** is a system administration project that introduces you to the world of virtualization. This project, part of the **42cursus**, involves setting up a virtual machine with specific security and configuration requirements. Through this project, I gained a deep understanding of system administration, virtualization, and security practices.

## Key Skills and Concepts Learned 🛡️

### Virtualization and System Setup 💻
- **VirtualBox/UTM**: Learned to use VirtualBox (or UTM) to create and manage virtual machines.
- **Operating System Installation**: Installed and configured a stable version of Debian or Rocky Linux.
- **Partitioning and LVM**: Created encrypted partitions using Logical Volume Management (LVM) for enhanced security and flexibility.

### Security Practices 🔒
- **SSH Configuration**: Configured SSH to run on a non-standard port (4242) and disabled root login for security.
- **Firewall Setup**: Configured UFW (or firewalld for Rocky) to restrict access to only the necessary ports.
- **Password Policies**: Implemented strong password policies to ensure user account security.
- **Sudo Configuration**: Set up and configured `sudo` with strict rules, including logging and custom error messages.

### Automation and Scripting 🤖
- **Bash Scripting**: Developed a `monitoring.sh` script in bash to display system information at regular intervals.
- **Cron Jobs**: Used cron to automate the execution of scripts and tasks.

### Code Organization and Best Practices 📏
- **Modular Code**: Organized configuration files and scripts for better readability and maintainability.
- **Norm Compliance**: Adhered to the 42 school's Norm, a set of coding standards that enforce good coding practices, ensuring consistency and readability across the project.

## Project Highlights 🌟

### Server Configuration 🖥️
- **SSH Service**: Configured SSH to run on port 4242 with user restrictions.
- **Firewall Rules**: Set up UFW/firewalld to allow only necessary traffic.
- **Hostname Configuration**: Set the hostname to include the user login and '42', e.g., `user42`.

### Monitoring Script 📜
- **System Information**: The `monitoring.sh` script displays essential system information, including CPU usage, memory usage, disk usage, and active connections.
- **Automated Execution**: Configured the script to run automatically every 10 minutes using cron.

### Bonus Features 🎁
- **Additional Services**: Set up additional services like a WordPress website with lighttpd, MariaDB, and PHP.
- **Custom Services**: Implemented a useful service of choice, enhancing my understanding of server management.

## Conclusion 🏁
Completing the **Born2beRoot** project was a significant milestone in my system administration journey. It provided me with a solid foundation in virtualization, security practices, and server management. The skills and knowledge gained through this project have prepared me to tackle more complex system administration challenges and contribute effectively to any IT team.

---

*This project is part of the 42cursus at [42 Network](https://www.42.fr/).*
