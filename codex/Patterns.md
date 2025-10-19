

# Notes

## Compiling
- feedback-loop: Add single sh file for building a program. Tell to start building and fixing errors

## Debugging
- feedback-loop: On harder problems like segmentation fault: tell to run in gdb and fix errors. This requires build feedback loop too.
- feedback-loop: Keep adding debug-printing under verbosity flags, and fixing them

## Multi agent mode
- Better and more expensive agents should be used for debugging, and to create tasks (TASKS.md). Then cheaper or free models should do those tasks.

## OS Root handling
- Usually models don't want to do "superuser tasks" or system installation, like Gentoo installation. Start by 'run in shell: "ssh root@<address> lsblk"' or similar to force it to use that. Then tell to do something remotely. Make sure that ssh works without asking for password.

