# Switch User Script (`0-iam_betty`)

This repository contains a simple script that switches the current user to the user `betty`. The script is designed to be minimal, using exactly **8 characters** for the command (`su betty`), plus 1 character for the newline.

## Purpose

The purpose of this repository is to demonstrate a basic script in Bash that changes the current user to another pre-existing user (`betty`). The script works by using the `su` command, which allows users to switch to another user account.

## Script Overview

- **Script Name**: `0-iam_betty`
- **Shebang**: `#!/bin/bash`
- **Command**: `su betty`
- **Length**: The command is exactly **8 characters** for switching the user, and the file includes a **newline character** (making the line 9 characters long when verified).

## How It Works

1. The script uses `su` to switch the user.
2. The `betty` user must already exist on the system.
3. The script is kept minimal and optimized to fit the requirement of using exactly 8 characters in the main command.

## Usage

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/your-username/0-iam-betty.git
