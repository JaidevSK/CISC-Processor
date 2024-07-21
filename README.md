# CISC-Processor
16 bit Small Scale CISC Architecture Based Processor developed in the course: Digital Systems

### Register File:
Consists of 16 registers, each 8 bits wide.
Used to store operands for instructions.
Instructions with 2 operands fetch one from the Register File and the other from the Accumulator.

### Accumulator:
Holds the result of arithmetic and logical operations.
Acts as one of the operands for instructions requiring two operands.

### Extended (EXT) Register:
8-bit register used during multiplication and division.
Stores higher-order bits during multiplication and quotient during division.

### C/B Register:
Holds the carry during addition and borrow during subtraction operations.

### Instruction Execution:
Each instruction executes in 1 clock cycle.
Division operations exclude 0 as a divisor.
Branch instructions can only branch within the program.

### Design Approach:
- Module Partitioning:
- - Divide the design into smaller modules like Register File, Accumulator, ALU (Arithmetic Logic Unit), Control Unit, etc.
- - Implement each module separately for modularity and ease of testing.

- Detailed Test Bench Codes:
- - Develop comprehensive test bench codes for each module to validate their functionality.
- - Test various scenarios, edge cases, and boundary conditions to ensure robustness.

- Synthesis and Integration:
- - After individual modules pass testing, synthesize them to ensure they meet performance and area requirements.
- - Integrate the modules together, ensuring proper communication and data flow between them.

- Final Testing:
- - Conduct thorough testing of the integrated processor to verify correct operation.
- - Test all instructions, including arithmetic, logical, branching, multiplication, and division, to validate the processor's functionality.
 
### Instruction Set:
![image](https://github.com/user-attachments/assets/a12bcf49-62d4-4d68-82c0-e9776d640e9c)
![image](https://github.com/user-attachments/assets/b4b963c5-2e91-4041-a615-ea54fa28edb7)

### Testing of the Processor:
Link: https://iitgnacin-my.sharepoint.com/:v:/g/personal/22110103_iitgn_ac_in/EUMQBQeL1YVBuIcSWm6jgx0Bjntteika2Dx9pDzkdJ6pqA?e=q0hH92&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D
