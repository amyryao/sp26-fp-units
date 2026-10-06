**Atlas NPU — Vector Floating-Point Units**

This repository contains my work on the vector floating-point unit
infrastructure used by the Atlas NPU project at UC Berkeley.

**Atlas NPU:**
github.com/ucb-bar/atlas-npu

**Upstream FP-unit repository:**
github.com/ucb-ee194-tapeout/sp26-fp-units

My contributions included:
- Integration of fixed-point Qm.n arithmetic for VPU operations
- Floating-point ↔ fixed-point conversion support
- BF16/FP16/FP32 parameterization for LUT-based operations
- Overflow/range handling for nonlinear floating-point operations
- Integration of vector floating-point support into the shared FP-unit library
