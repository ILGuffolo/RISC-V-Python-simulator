# RISK-V-Python-simulator
a small project, simulating a RV32I architecture on python

# Instruction
write the code with any tool you like and paste it into the "assembly sim" folder as "program.txt" then execute main.py

# Coming updates
completing instruction set

ecalls to read and print to/from terminal

global variables

stack

optimizzation

QoL

# Current supported commands

(r) -> value in register r
m[i] -> memory at index i

add rd rs1 rs2 : (rd) = (rs1) + (rs2)

sub rd rs1 rs2 : (rd) = (rs1) - (rs2)

addi rd rs1 imm : (rd) = (rs1) + (imm)

lw rd rs1 imm : (rd) = M[rs1 + imm]

sw rs1 rs2 : M[rs1 + imm] = (rs2)

beq rs1 rs2 imm : if rs1 == rs2: pc += imm

beq rs1 rs2 imm : if rs1 != rs2: pc += imm

jal rd imm : (rd) = pc + 4; pc += imm

jalr rd rs1 imm : (rd) = pc + 4; pc += (rs1) + imm


