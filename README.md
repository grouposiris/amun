<h2> amun: AMBA APB Bus IP Core </h2>

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

<p align="center">
  <img src="docs/images/results/amun_logo.png" width=250 alt="Amun IP logo">
</p>

## Introduction

**Amun** is a configurable **AMBA APB (Advanced Peripheral Bus) IP core** that implements the APB protocol for efficient and low-power peripheral interconnects in FPGA and ASIC designs.  
It can operate as an APB master or slave, making it ideal for system-on-chip (SoC) architectures that require a lightweight, high-performance bus interface.

The AMBA APB protocol is widely used for connecting low-bandwidth peripherals due to its simple timing, low gate count, and power efficiency.  
**Amun** delivers full compliance with the AMBA APB3/APB4 specifications, while offering flexibility, scalability, and ease of integration.

Key features of Amun include:
- **Protocol Compliance:** Fully compliant with AMBA APB3 and APB4 specifications.
- **Master or Slave Modes:** Configurable to function as an APB bus master or slave.
- **Configurable Data and Address Widths:** Supports multiple bus widths to suit diverse system needs.
- **Low Power Design:** Optimized for minimal logic usage and reduced dynamic power.
- **Wait State Insertion:** Adjustable timing to interface with peripherals of varying latency.
- **Error Handling:** Implements `PSLVERR` signaling for robust error reporting.
- **Easy Integration:** Simple interface for direct connection to controllers, bridges, or peripherals.
- **Scalable Architecture:** Multiple instances can be combined to form complex APB interconnects.
- **Verification Suite:** Includes simulation models and testbenches for functional validation.

**Amun** is suitable for:
- Peripheral interconnects in SoCs
- APB master/slave endpoints in protocol bridges (e.g., SPI-to-APB)
- Low-latency register and control signal access
- Integration between processors and custom hardware modules

Refer to the [documentation](docs/) for configuration parameters, integration guides, and simulation examples.
