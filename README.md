# SV_Projects
This collection showcases RTL designs and object-oriented testbenches for key digital components. Each module is simulated and verified using class-based SystemVerilog testbenches, all runnable on EDAPlayground or any simulator like Synopsys VCS or Mentor Questa.

| Projects      | Description                                                |
|---------------|------------------------------------------------------------|
| D Flip-Flop   | Positive-edge triggered DFF with async reset               |
| FIFO          | First-In First-Out buffer design with testbench            |
| UART          | Universal Asynchronous Receiver Transmitter (TX/RX)        |
| SPI           | Serial Peripheral Interface protocol module                |
| I2C           | Inter-Integrated Circuit bus protocol implementation       |
| AXI4-Lite     | AXI4-Lite protocol-compliant slave memory interface        |

Each folder contains:
- RTL Design (`*.sv`)
- Testbench using OOP (`*_tb.sv`)
- Simulation result (`simulation.png`)
- Detailed README.md for setup and explanation

## How to Run

You can simulate each project using:
- [EDAPlayground](https://www.edaplayground.com/)
- If you create a account using your personal email :
  Languages and Libraries select : SystemVerilog/UVM
  Tools and simulators select: Aldec Riviera Pro 2023.04
  Click on 'Open EPWave after run' to view the waveforms

## Folder Structure for Repo
```
SV_Projects/
├── README.md                   # Top-level overview
├── assets/                     # Central folder for all simulation images 
├── DFF/
│   ├── dff.sv
│   ├── dff_tb.sv
│   └── README.md
├── FIFO/
│   ├── fifo.sv
│   ├── fifo_tb.sv
│   └── README.md
├── UART/
│   ├── uart.sv
│   ├── uart_tb.sv
│   └── README.md
├── SPI/
│   ├── spi.sv
│   ├── spi_tb.sv
│   └── README.md
├── I2C/
│   ├── i2c.sv
│   ├── i2c_tb.sv
│   └── README.md
└── AXI4-Lite/
    ├── axi4_lite.sv
    ├── axi4_lite_tb.sv
    └── README.md
```


