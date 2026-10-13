# Morgan Huberty 

**Computer Engineering @ Johns Hopkins University · Class of 2027**

Senior focused on RTL design, design verification, and FPGA/ASIC engineering. I build and verify digital hardware in VHDL and Verilog, and I'm working toward ASICs for AI acceleration and edge computing.

### ⚙️ Current Focus & Exploration
* **Currently Building:** A ZipCPU soft-core processor build on an Artix-7 FPGA, simulating each design with Verilator and C++ test drivers before validating it on hardware. Formal verification with SymbiYosys is next.
* **Currently Learning:** SystemVerilog and SystemC.
* **Interests:** Computer architecture, hardware for AI acceleration, and the semiconductor industry and supply chain.

### 🔬 Projects
* **[UART Transceiver](https://github.com/mhubert3/FPGA-Serial-UART)** - *VHDL*
  * UART transmitter and receiver (8N1, 115,200 baud from a 12 MHz clock) with a two-flop RX synchronizer and mid-bit sampling. Verified with a self-checking testbench, then on hardware via loopback.
* **[I²C Master Controller](https://github.com/mhubert3/FPGA-Serial-I2C)** - *VHDL*
  * FSM-based I²C master with repeated start, ACK/NACK, clock stretching, and open-drain SDA/SCL. Validated end-to-end on hardware with a PIC16F18326 slave.
* **[Set-Associative Cache Simulator](https://github.com/mhubert3/Cache-Simulator)** - *C/C++*
  * Configurable cache simulator (LRU/FIFO replacement, write policies) reporting hit/miss counts and cycle totals from memory traces.
* **[Multithreaded Key/Value Store](https://github.com/mhubert3/KeyValue-Store)** - *C++*
  * In-memory K/V store with custom message serialization and a multithreaded server with table-level locking.
* **[Big Integers](https://github.com/mhubert3/Big-Int)** - *C++*
  * Arbitrary-precision integer class supporting core arithmetic, bitwise operations, and hex/dec conversions.

### 📬 Connect with Me
* **Engineering Portfolio:** [mhubert3.github.io](https://mhubert3.github.io/)
* **LinkedIn:** [morganhuberty](https://www.linkedin.com/in/morganhuberty/)
