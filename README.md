# RAM-DESIGN

COMPANY: CODTECH IT SOLUTIONS

NAME: EEDULAKANTI RAMESH REDDY

INTERN ID: COD123

DOMAIN: VLSI

DURATION: 4 WEEKS

MENTOR: NEELA SANTOSH


# DESCRIPTION OF MY TASK

A synchronous RAM module is a type of memory that follows a clock signal, ensuring all read and write operations happen at precise intervals. This makes it different from asynchronous RAM, which does not rely on a clock pulse. In synchronous RAM, every action—whether storing new data or retrieving existing information—happens when the clock pulses, keeping operations predictable and efficient.

The module consists of several key components. The clock controls the timing of operations, ensuring that data is written and read at the correct moments. The write enable signal determines whether new data should be stored in RAM. If this signal is active, the RAM accepts new input. The address specifies the location where the data should be stored or retrieved. The data input is the information being fed into the RAM for storage, while the data output is the information retrieved from memory when needed.

The process of writing and reading data in synchronous RAM follows a structured method. When the clock pulses and the write enable signal is high, the new data input is stored in RAM at the designated address. If the write enable signal is low, the memory retrieves stored information from that address, making it available as output. Because everything happens in sync with the clock, there are no random delays or unpredictable memory access issues.

To implement a synchronous RAM module, hardware designers use Verilog, a Hardware Description Language (HDL) that defines how digital circuits should function. In a simple Verilog model, designers define parameters like data width and address width, create a memory array to store values, and set up a clock-driven process to manage read and write operations efficiently.

<img width="549" alt="Image" src="https://github.com/user-attachments/assets/c3ee3440-c630-4efc-a7ab-fa5b6017097d" />
<img width="949" alt="Image" src="https://github.com/user-attachments/assets/9fb1cc2e-3eaf-4130-8bef-2eab4092c07e" />

