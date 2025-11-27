# ELF
Executable Linkable Format: Working examples in Assembly

This repository contains example programs for the FASM and NASM assemblers on Intel machines. Both 32 and 64 bit editions are included.

The key thing about these examples is that the ELF headers are manually created with directives specifically for those Assemblers. For FASM this wasn't actually necessary but for NASM it is to be able to create executables without a linker.

Only Linux examples are present because that is the environment where ELF files are used. However, I did once run a Linux Assembly program on Windows using the Windows subsystem for Linux, though using Linux natively is more convenient.