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
## Screenshots
<img width="960" alt="Screenshot 2024-01-10 113350" src="https://github.com/parvsablok/Xenonstack_Task1/assets/99950588/0fd5d5ad-e5aa-43dc-90f4-1e7a331a9257">
<img width="290" alt="Screenshot 2024-01-10 113556" src="https://github.com/parvsablok/Xenonstack_Task1/assets/99950588/c63c7d0a-5074-4c56-a01b-6a04097ac56d">
<img width="187" alt="Screenshot 2024-01-10 113705" src="https://github.com/parvsablok/Xenonstack_Task1/assets/99950588/04d7c2f2-f8f4-404f-8d43-64661d947f28">
<img width="949" alt="Screenshot 2024-01-10 115309" src="https://github.com/parvsablok/Xenonstack_Task1/assets/99950588/aad45bf9-c07c-498b-a4cb-cd6690567a5b">
<img width="351" alt="Screenshot 2024-01-10 115352" src="https://github.com/parvsablok/Xenonstack_Task1/assets/99950588/e85b7d84-0368-492e-b7d0-2a474c5a1e0b">
<img width="180" alt="Screenshot 2024-01-10 120224" src="https://github.com/parvsablok/Xenonstack_Task1/assets/99950588/0544a4ce-ca01-4ff9-9e7d-bce9d6d75848">
<img width="72" alt="Screenshot 2024-01-10 143329" src="https://github.com/parvsablok/Xenonstack_Task1/assets/99950588/76d561b6-1021-4bfc-9327-946f724d3411">
<img width="190" alt="Screenshot 2024-01-10 120412" src="https://github.com/parvsablok/Xenonstack_Task1/assets/99950588/7ed58dce-53bf-4001-b835-f9738d62a28c">
<img width="266" alt="Screenshot 2024-01-10 144149" src="https://github.com/parvsablok/Xenonstack_Task1/assets/99950588/b479c86e-ac34-4db0-9c07-a5c2003d0169">


