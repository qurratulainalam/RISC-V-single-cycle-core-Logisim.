# RISC-V-single-cycle-core-Logisim.
### Introduction:
This repository contains RISC-V Single Cycle 32 Bit Processor simulated on Logisim. This circuit contains 32 bit ALU, 32 bit Data Bus, 16KB ROM/RAM, 12 Bit Address Bus for both RAM MAR(memory address register). Register File contains 32 Registers with data width of 32 bits,and some Troubleshooting codes to verify all the circuit components.
### components:
1.ALU
2.Register File
3.Memory Address Register
4.Immediate Generation
5.Control Unit
6.Type Decode
7.Control Decode
8.RAM
9.Branch Circuit
10.Program Counter
### instructor:
*sir zeeshan rafique
### Pre-Req Tools
*logisim
*venus stimulator
### instructions that can be stimulated:
following are the 27 instructions that are stimulated and checked on this single cycle cpu,

    1.add
    2.addi
    3.sub
    4.xor
    5.and
    6.slt
    7.sltu
    8.sll
    9.srl
    10.sra
    11.lw
    12.jalr
    13.slli
    14.srli
    15.srai
    16.slti
    17.sltiu
    18.sw
    19.auipc
    20.lui
    21.li
    22.beq
    23.bne
    24.blt
    25.bge
    26.bltu
    27.bgeu
   ### Five Stages of Instruction execution:
   * Stage 1: InstrucLon Fetch 
   * Stage 2: InstrucLon Decode 
   * Stage 3: ALU (ArithmeLc-Logic Unit) 
   * Stage 4: Memory Access 
   * Stage 5: Register Write 
   ![execution of data path](C:\Users\Lenovo\Downloads\eee.png?raw=true "Title")
