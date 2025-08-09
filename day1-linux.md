# Day 1 — Linux Basics

## Date
2025-08-09

## Goal
- Set up Linux environment
- Learn basic file & navigation commands
- Document process for future reference

## Commands Learned

| Command | Purpose | Example Usage |
|---------|---------|---------------|
| `pwd` | Shows current directory | `pwd` |
| `ls` | Lists files in directory | `ls -la` |
| `cd` | Change directory | `cd /home` |
| `mkdir` | Create directory | `mkdir test` |
| `touch` | Create file | `touch file1` |
| `nano` | Edit file | `nano file1` |
| `cat` | Display file content | `cat file1` |
| `cp` | Copy files | `cp file1 file2` |
| `mv` | Move/Rename files | `mv file2 test/` |
| `rm` | Delete files | `rm file1` |

## Practice Exercise
- Created `test` directory
- Made `file1` inside it
- Edited and saved file with `nano`
- Copied and moved files
- Deleted a file

## Mistakes / Errors & Fixes
- Tried running `mount` without sudo → Got “must be superuser” error → Learned about permissions.
- Forgot `cd` into the right directory before running commands.

## Next Steps
- Learn file permissions (`chmod`, `chown`)
- Start simple Bash scripts
