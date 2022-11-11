The purpose of this program is to translate assembly mnemonics written in the HACK's native machine language into binary instructions.

To compile: g++ -std=c++11 Assembler.cpp parser.cpp translate.cpp
To run: ./a.out insert_asm_filename_here.asm symbolmap.txt

The binary code will be output to binary.hack, as it is hard-coded into the Assembler.cpp program itself.

This program is capable of translating any .asm program written in the HACK machine language, but the programs available by default here include: Add, Max, Rect, and Pong, all with the .asm file extension.