# Single-Port Synchronous RAM

### Author Information
- **Name:** MADHAVI ARADHYULA  
- **Company:** CODTECH IT SOLUTIONS  
- **ID:** CT08DOW  
- **Domain:** VLSI  
- **Duration:** Dec 2024 to Jan 2024  
- **Mentor:** SRAVANI GOUNI

---

## Project Overview  
The **Single-Port Synchronous RAM** module is designed to implement a basic memory block that supports read and write operations at a specific address. This design is based on a synchronous memory model, where both read and write operations are controlled by a clock signal. The module allows data to be written to a specified address and read from the same address using the same data bus.

This **Single-Port RAM** operates with:
- **Write Enable (we):** When active, it writes data to the specified address.
- **Chip Select (cs):** When active, it enables the memory module for both reading and writing.
- **Output Enable (oe):** When active, it allows reading data from the memory location.
- **Address (addr):** Specifies the memory location for read or write operations.
- **Data (data):** Bidirectional line for data input/output.

The RAM module uses a **clock (clk)** to synchronize the read/write operations, making it suitable for high-speed applications. This simple design is ideal for understanding the behavior of single-port memory systems and serves as a foundation for more complex memory designs in digital systems.

---

## Features
- **Write Operation:**  
  Data is written to a specific memory location when **Write Enable (we)** is active.

- **Read Operation:**  
  Data is read from a specific memory location when **Output Enable (oe)** is active and **Write Enable (we)** is not.

- **Synchronous Operation:**  
  The memory works synchronously with the clock signal, ensuring reliable timing for both read and write operations.

- **Configurable Parameters:**  
  The RAM module has customizable **address width**, **data width**, and **depth** through parameters:
  - **ADDR_WIDTH:** Width of the address bus.
  - **DATA_WIDTH:** Width of the data bus.
  - **DEPTH:** Number of memory locations.

- **Bidirectional Data Bus:**  
  The **data** line serves as both input and output, with the direction controlled by the **we** and **oe** signals.

---

## Tools Used
- **Verilog:**  
  The **Single-Port Synchronous RAM** design is implemented in **Verilog HDL**, providing an efficient and flexible description of the hardware.

- **EDA Playground:**  
  The project was simulated using **EDA Playground**, an online platform for running Verilog code and visualizing simulation results.

- **GTKWave:**  
  The waveform output generated from the simulation is visualized using **GTKWave**, allowing for easy inspection of memory read and write operations.

---
## Simultion Results

![image](https://github.com/user-attachments/assets/723db4d5-71bf-4c85-9420-b4d5016094c9)


