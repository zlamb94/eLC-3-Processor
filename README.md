# eLC-3-Processor
Student Project
Designing an eLC-3 processor, a simplified version of the 16 bit LC3 processor. Processor takes in a 16 bit hexadecimal input, translates to assembly instruction and executes said instruction. Uses the Logisim software to implement the processor. FSM designates the Finite State Machine which is implemented in eLC-3/Controller.circ. Controller is designed from the truthtable.xlsx file to specify state transitions.

To use the processor:
- Load image into memory, image should contain legitimate LC3 assembly code in hexadecimal format. (test.asm, test.hex files can be used to accomplish this)
- Run clock to cycle through different stages of executing the instruction
