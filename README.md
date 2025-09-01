RAM DESIGN

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: NIHARIKA VADLA

*INTERN ID *: CT06DZ602

*DOMAIN*: VLSI

*DURATION*: 6 WEEKS

*MENTOR*: NEELA SANTHOSH


//DESCRIPTION


The primary objective of this task is to design and implement a synchronous Random Access Memory (RAM) module using Verilog Hardware Description Language (HDL), and to simulate its functionality on the Xilinx Vivado Design Suite. Memory modules form one of the most essential components in any digital system, as they are used to store, retrieve, and manipulate data. In modern computer systems, RAM is widely used because of its fast access time and ability to temporarily store data during program execution. By designing a simplified synchronous RAM, this project focuses on introducing the fundamental concepts of memory architecture, synchronous operations, and verification of digital hardware through simulation.
Synchronous RAM operates in synchronization with a clock signal. Unlike asynchronous memory, where read and write operations can occur at any time, synchronous RAM ensures that both operations are triggered only on the active edge of the clock (rising or falling, depending on the design). This synchronization improves timing predictability and reliability, which is crucial in digital circuits such as microprocessors, FPGAs, and embedded systems.

In this project, the designed synchronous RAM supports two basic operations:

Write Operation – Data is written into a specific memory location when the write enable (WE) signal is active.

Read Operation – Data is read from the specified memory location when the read enable (RE) signal is active.

Both operations are performed in accordance with the clock signal, ensuring that the memory behaves deterministically.
The RAM module was implemented in Verilog HDL, a hardware description language commonly used for digital system design. The design follows a modular structure, where the RAM block is parameterized for address width and data width. This allows flexibility in scaling the memory size as needed.

A testbench was also written in Verilog to verify the design. The testbench simulates various scenarios such as writing data to specific memory locations, reading it back, and checking correctness under different conditions. The waveform outputs in Vivado were analyzed to ensure that the RAM behaves as expected.
Tools and Simulation

The implementation and simulation were carried out using Xilinx Vivado, which is an industry-standard tool for FPGA and digital circuit design. Vivado provides a robust simulation environment that allows visualization of timing waveforms, making it possible to validate the synchronous behavior of the RAM. During simulation:

The write operation was tested by applying a clock signal, setting the write enable high, and providing input data and address lines.

The read operation was tested by enabling the read signal and checking that the correct data appears on the output

//SIMULATION OUTPUT
<img width="1904" height="1073" alt="Image" src="https://github.com/user-attachments/assets/42fa933d-97fd-4bd7-a061-b92d0a540607" />
