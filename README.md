# RISC-V RV32I 5-Stage Pipeline Core

The implementation of an **RV32I RISC-V CPU core** using a classic 5-stage pipeline:


This project emphasizes clean microarchitecture components, correctness, and testability.

## Features

- **RV32I integer base instruction support** — ALU operations, immediate generation, loads/stores and branches.  
- **Five pipeline stages**: IF / ID / EX / MEM / WB.  
- **Register file** with writeback in the WB stage.  
- **Forwarding (bypass) unit** to resolve RAW hazards and reduce stalls.  
- **Load-use hazard detection** with a single-cycle stall when required.  
- **Synchronous memory model** for instruction and data (simple memory interface suitable for simulation).  
- **Testbenches and assembly test vectors** for functional verification and validation.

---

