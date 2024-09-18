# Synchronization Script for Remote Directories

This script is used to sync files from a remote directory to a local directory and move them to a final destination while handling sensitive information securely.

## Requirements

- `sshpass` for handling password-based SSH connections.
- Remote server access with SCP and SSH enabled.
- Correct permissions for local directories.

## Usage

1. Set the required environment variables:

export REMOTE_USER="your_remote_user"
export REMOTE_HOST="your_remote_host"
export REMOTE_PASS="your_remote_password"
export REMOTE_BASE_DIR="/remote/base/directory"
export LOCAL_BASE_DIR="/local/base/directory"
export LOG_FILE="/path/to/log/file.log"
export FINAL_DESTINATION="/path/to/final/destination"
