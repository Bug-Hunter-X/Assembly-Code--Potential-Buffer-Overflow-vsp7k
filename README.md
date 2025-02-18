# Assembly Code Bug: Potential Buffer Overflow

This repository demonstrates a potential buffer overflow vulnerability in a short assembly code snippet. The code lacks bounds checking, which makes it vulnerable to exploitation if the input values (ebx, esi, edi) are not carefully controlled.

The `bug.asm` file contains the vulnerable code.  The `bugSolution.asm` file provides a corrected version with bounds checking (though the exact implementation of bounds checking depends on the specific requirements and context).