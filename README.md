RISC-V Mentorship: Tower of Hanoi Demo
📖 Project Description
This script demonstrates the classic Tower of Hanoi algorithm using Python. It is designed to highlight fundamental computer science concepts—Recursion and Iteration—and how they map to RISC-V machine instructions.

⚙️ RISC-V Relevance
The code is structured to show two specific control flow patterns:

Recursion (Stack Management):
The solve_hanoi function calls itself.
RISC-V Mapping: This corresponds to jal (Jump and Link) instructions. It demonstrates how the processor uses the Stack Pointer (sp) to save and restore function contexts.
Iteration (Branching):
The simulation loop processes moves step-by-step.
RISC-V Mapping: This corresponds to conditional branches like bne (Branch if Not Equal) and loop counters, which are crucial for pipeline efficiency.
🚀 How to Run
Open your terminal and execute:

bash

Riduci
Salva
Copia
1
