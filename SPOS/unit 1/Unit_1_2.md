# Evolution of Components of Systems Programming

### Text Editors:
---
- Earliest tool in systems programming
- Used to `create and edit source code` in high-level and assembly languages
- Evolution:
    1. Started with line-by-line editors `ed`
    2. Then came multiline simple editors `notepad`
    3. Then came full featured editors with syntax highlighting `vs code, vim`

### Assembler: 
---
- Assembler is the tool used to assemble the source code written in the `assembly language to the machine language`
- They were the first generation translators 
- Evolution:
    1. Initially Simple `one pass assemblers`
    2. Now `multi-pass` assemblers with `macros` and `optimizations`

### Macros
---
- Macros are `reusable code templates` in assembly language
- Helps reducing repetative code and increases `modularity`
- `Macro Processors` evolved to expand macros during assembly
- widely used in early and modern assemblers

### Compilers
---
- compilers translates high level languages like c/c++ to assembly or machine code
- Performs optimization and syntax checking
- Evolution:
    1. Early compilers like FORTON (1957) were simple
    2. Now we have compilers like GCC, LLVM, etc

### Interpreter
---
- Executes source code line by line without converting it to machine code
- Easier debugging and dynamic execution
- Evolution:
    1. Started with BASIC and LISP
    2. Modern examples like python, javascript interpreter

### Loaders
---
- Loads executable code into memory and prepares it for execution
- Handles memory allocation and relocation
- Evolution:
    1. Early system had simple loaders (absolute)
    2. Later introduced relocating and dynamic loaders (Used in modern OS)

### Linkers
---
- Combines object files into a single executable
- Resolves symbols refrences across modules
- Evolution:
    1. Static Linkers -> Dynamic Linkers (DLL, shared libraries)
    2. Advance linkers also optimize binaries

### Debugger
---
- Tool for detecting and fixing errors in programs
- Provides breakpoints, memory inspection, step by step execution
- Evolution:
    1. started as command line tools
    2. Now full IDEs include GUI Debuggers

### Device Drivers
---
- Software that allows the OS to communicate with the hardware
- Evolution:
    1. Early drivers were Hardware specific
    2. Now drivers are modular, portable and often developed with OS Support

### Operating System
---
- Operating System manages software and hardware resources
- Provides security, system services, memory management, file systems, multitasking
- Evolution:
    - Early systems were batch OS (No user interaction)
    - Later cam multiprogramming, multitasking, real time OS
    