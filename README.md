# UART Controller ASIC Project
UART (Universal Asynchronous Receiver/Transmitter) controller developed in Verilog and implemented through a complete ASIC digital design flow using the IHP SG13G2 PDK and LibreLane/OpenLane-based tools.

## Project Specifications
- Circuit Type: Synchronous Digital
- Description Language: Verilog HDL
- Protocol: UART
- UART Format: 8N1
- Data Width: 8 bits
- Baud Rate: 9600 bps
- Clock Frequency: 100Mhz
- Clock Period: 10ns
- PDK: IHP SG13G2
- Physical FLow: LibreLane

  ## RTL Modules

  ### Baud Generator
  Generates the baud tick signal used by the UART transmitter and receiver timing logic.

  ### UART TX
  Implements the UART transmission logic using the 8N1 protocol format.

  ### UART RX
  Implements the UART reception logic and reconstructs the received byte from the serial input stream.

  ### UART TOP
  Top-level module integrating transmitter, receiver and baud generator.

  ## Technologies Used
  - Verilog HDL
  - Icarus Verilog
  - GTKWave
  - LibreLane
  - Magic
  - NGSpice
  - Xschem
  - IHP SG13G2 PDK
 
  ## Author
  Leonardo Fernandes Cavalcante
  
