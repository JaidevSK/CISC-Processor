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
https://iitgnacin-my.sharepoint.com/:v:/g/personal/22110103_iitgn_ac_in/EUMQBQeL1YVBuIcSWm6jgx0BnMzWYttBsIBk3BEvdV6LcQ?e=1NHFhW&nav=eyJwbGF5YmFja09wdGlvbnMiOnt9LCJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbE1vZGUiOiJtaXMiLCJyZWZlcnJhbFZpZXciOiJwb3N0cm9sbC1jb3B5bGluayIsInJlZmVycmFsUGxheWJhY2tTZXNzaW9uSWQiOiJjYWMyODU1Yi1jNmFlLTQxNzMtOGE3ZC00ZjM1YjAwZWIxZWUifX0%3D


<iframe src="https://iitgnacin-my.sharepoint.com/personal/22110103_iitgn_ac_in/_layouts/15/embed.aspx?UniqueId=07051043-d58b-4185-b887-125a6ea3831d&nav=%7B%22playbackOptions%22%3A%7B%22startTimeInSeconds%22%3A0%7D%7D&embed=%7B%22ust%22%3Atrue%2C%22hv%22%3A%22CopyEmbedCode%22%7D&referrer=StreamWebApp&referrerScenario=EmbedDialog.Create" width="640" height="360" frameborder="0" scrolling="no" allowfullscreen title="Digital Systems Final Lab.mp4"></iframe>
