# RISCV-shell

A basic unix shell using the RISCV operating system in C

This project utilises RISC-V, an open source UNIX operating system, my shell program is run under my_shell.c, which is in the user directory.

The shell can perform basic linux commands and follows the logic of pipes, redirects and concatenation, compatible with basic comands such as ls, cd, grep, cat touch.

BUILDING AND RUNNING XV6

You will need a RISC-V "newlib" tool chain from
https://github.com/riscv/riscv-gnu-toolchain, and qemu compiled for
riscv64-softmmu. Once they are installed, and in your shell
search path, you can run "make qemu".
