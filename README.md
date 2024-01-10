# Xenonstack_Task1

## Overview

`internsctl` is a custom Linux command designed for intern operations. It provides a set of functionalities for managing CPU information, memory information, user operations, and file-related actions on a Linux system.

## Features

- **Command Sections:**
  - **A. Basic Commands:**
    - `cpu getinfo`: Display CPU information.
    - `memory getinfo`: Display memory information.
  - **B. User Operations:**
    - `user create <username>`: Create a new user with login access and a home directory.
    - `user list`: List all regular users.
    - `user list --sudo-only`: List users with sudo permissions.
  - **C. File Operations:**
    - `file getinfo <file-name>`: Get information about a file.
      - Options:
        - `--size, -s`: Print file size.
        - `--permissions, -p`: Print file permissions.
        - `--owner, -o`: Print file owner.
        - `--last-modified, -m`: Print last modified time.

## Usage

```bash
# Display CPU information
internsctl cpu getinfo

# Display memory information
internsctl memory getinfo

# Create a new user
internsctl user create <username>

# List all regular users
internsctl user list

# List users with sudo permissions
internsctl user list --sudo-only

# Get information about a file
internsctl file getinfo <file-name>

# Get specific information about a file
internsctl file getinfo --size <file-name>
internsctl file getinfo --permissions <file-name>
internsctl file getinfo --owner <file-name>
internsctl file getinfo --last-modified <file-name>
```
## Installation
Clone the repository and make the script executable:
- git clone https://github.com/parvsablok/Xenonstack_Task1.git
- cd internsctl
- chmod +x internsctl
## Diagram
![Untitled Diagram drawio](https://github.com/parvsablok/Xenonstack_Task1/assets/99950588/20066133-2f9f-4677-a56b-f42ff36b0034)
