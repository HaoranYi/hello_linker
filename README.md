An example linker script for embedded system.

(ARM Cortex Mx)

Makefile - commands to compile, link source code
stm32_ls.ld -  a linker script that demonstrate entrypoint, section, symbol table (from final.elf)
stm32_startup.c - startup code, `Reset_handler`  runs before main.
  - use external symbol to move data from ROM to RAM and zero .bss sections.
