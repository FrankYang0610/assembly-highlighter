# assembly-highlighter 

This is a **Visual Studio Code extension** for assembly language highlight. 

A wide range of **x86** assembly keywords are supported now:
- Registers, e.g., `EAX`, `AX`, `AL`, `AH`.
- MMX registers, e.g., `MM0`, `MM1`, `MM2`, `MM3`. 
- Floating-point registers, e.g., `ST`. 
- Flags bits, e.g., `CF`, `PF`, `AF`, `ZF`.
- Basic assembly instructions, e.g., `MOV`, `CALL`, `PUSH`, `POP`.
- Operation instructions, e.g., `ADD`, `SUB`, `MUL`.
- Section directives, e.g., `.text`, `.data`.
- Assembler pseudo-instructions, e.g., `.global`, `.extern`.
- Macro directives, e.g., `.macro`, `.ifdef`, `ifndef`.
- Debugging-related directives, e.g., `.type`, `.size`.
- Data allocation directives, e.g., `.byte`, `.word`.
- Other directives, e.g., `.align`, `.section`.

In the future, **ARM** and other assembly language instruction set keywords will also be gradually added. 

## References
You can find all the information about the **x86 instruction set** at [Archived: Intel Architecture
Software Developer’s Manual, Volume 2: Instruction Set Reference](https://web.archive.org/web/20090611193346/http://download.intel.com/design/PentiumII/manuals/24319102.PDF). 

#### Author: Frank Yang (@FrankYang0610)