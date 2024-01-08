# RaySoul

**The development has been paused because the developers lack of time.**

A fast, lightweight, portable and secure runtime based on 64-bit RISC-V
Unprivileged ISA Specification.

We believe RISC-V will be the better solution than WebAssembly because the
RISC-V ISA design is more elegant. We hope through RISC-V ISA we can find a
solution that makes us less tangled with ISA designing issues and make RISC-V
ISA immortal even if no hardware uses RISC-V ISA.

## Planned Features

- Support for RV64GCV with [Dynamic Binary Translation].
- Provide emulation for some Linux syscalls.
- Support for running under bare-metal environment like UEFI.
- Research for heterogeneous acceleration support.

[Dynamic Binary Translation]: https://en.wikipedia.org/wiki/Binary_translation#Dynamic_binary_translation

## Planned Scenarios

- Softwares need plugin system
![NanaZip](Documents/NanaZip.png)

- Unikernel for paravirtualization guests
![Mobility](Documents/Mobility.png)
