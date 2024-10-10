# sysopctl - v0.1.0

`sysopctl` is a custom command-line tool designed to manage Linux system services, processes, and system health efficiently. This tool provides a user-friendly interface for handling routine system administration tasks, such as managing services, checking system loads, monitoring processes, and performing system backups.

## Features

- **List Active Services**: View all currently active system services.
- **Start/Stop Services**: Easily start or stop specific system services.
- **Monitor System Load**: Display real-time system load averages.
- **Check Disk Usage**: View detailed disk usage statistics.
- **Monitor Processes**: Monitor real-time system processes.
- **Analyze System Logs**: Analyze recent critical system logs.
- **Backup System Files**: Perform system file backups.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
  - [List Services](#list-services)
  - [Start a Service](#start-a-service)
  - [Stop a Service](#stop-a-service)
  - [System Load](#system-load)
  - [Disk Usage](#disk-usage)
  - [Monitor Processes](#monitor-processes)
  - [Analyze Logs](#analyze-logs)
  - [Backup System](#backup-system)
- [Sample Screenshots](#Sample-Screenshots)


## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/sysopctl.git
    cd sysopctl
    ```

2. **Make the script executable**:
    ```bash
    chmod +x sysopctl
    ```

3. **Add the script to your PATH** (optional for global use):
    ```bash
    sudo cp sysopctl /usr/local/bin/
    ```

## Usage

Once the script is installed and made executable, you can use the following commands to perform system tasks.

### List Services
To list all active services:
```bash
sysopctl service list
```
## Sample Screenshots

**Disk Usage**  
![disk usage](https://github.com/user-attachments/assets/c485f711-b307-4080-83b4-40d1b13a8b4d)

**Help**  
![help](https://github.com/user-attachments/assets/4a8fd8f0-6351-446f-a554-ff92b6592b4d)

**Process Monitor**  
![Process monitor](https://github.com/user-attachments/assets/64df6889-7b98-4ecd-9f60-9d8f76882489)

**System Load**  
![system load](https://github.com/user-attachments/assets/3ea3c5fd-e0e3-449e-8148-1c006b64b1b9)













