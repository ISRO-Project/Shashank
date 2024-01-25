# Detailed Report on Processors  ISRO

## Most common Architectures :- 
CISC (Complex Instruction Set Computing):

### 1. CISC architectures have a large set of instructions, some of which can perform complex operations.
- Instructions vary in length and complexity.
- Examples: x86 (Intel, AMD), Motorola 68k.

### 2. RISC (Reduced Instruction Set Computing):
- RISC architectures have a smaller set of simple and frequently used instructions.
- Instructions are typically of fixed length.
- Emphasizes a smaller set of instructions with higher execution speed.
- Examples: ARM, MIPS, PowerPC.

### 3. EPIC (Explicitly Parallel Instruction Computing):
- EPIC architectures focus on parallel processing and execution.
- Example: Intel Itanium.

### 4. VLIW (Very Long Instruction Word):
- Similar to EPIC, VLIW architectures use long instruction words to represent parallel operations.
- The compiler schedules the instructions for parallel execution.
- Examples: TI C6x, IA-64.

### 5. Superscalar:
- Superscalar architectures execute multiple instructions simultaneously.
- Multiple execution units are used to achieve parallelism.
- Instructions are dynamically scheduled for execution.
- Examples: Intel Pentium, AMD Athlon.

### 6. Vector Processors:
- Vector processors operate on vectors or arrays of data with a single instruction.
- Suited for tasks involving repetitive and parallelizable operations.
- Examples: Cray supercomputers, NEC SX series.

### 7. SIMD (Single Instruction, Multiple Data):
- SIMD architectures process multiple data elements in parallel using a single instruction.
- Well-suited for parallelizable tasks like multimedia processing.
- Examples: Intel SSE/AVX, ARM NEON.

### 8. MIMD (Multiple Instruction, Multiple Data):
- MIMD architectures have multiple independent processors that can execute different instructions simultaneously.
- Suited for parallel processing and multitasking.
- Examples: Multi-core processors, clusters, distributed computing systems.

### 9. Distributed Processors:
- Distributed processors consist of multiple processors working together over a network.
- Each processor may have its own memory and execute its own set of instructions.
- Examples: Beowulf clusters, modern cloud computing infrastructures.

### 10. Neuromorphic Processors:
- Neuromorphic processors are designed to mimic the structure and functionality of the human brain.
- They are optimized for tasks related to artificial intelligence and neural networks.
- Examples: IBM TrueNorth, SpiNNaker.




# There are several types of processors

There are several types of processors, each with its own architecture and characteristics. Here are some of the most prominent types:

### 1. x86 Architecture:
- Dominant in personal computers and servers.
- Developed by Intel and AMD.
- Widely used in desktops, laptops, and servers.
- Examples: Intel Core series, AMD Ryzen series.

### 2. ARM Architecture:
- Common in mobile devices, embedded systems, and increasingly in servers.
- Known for its power efficiency.
- Used in smartphones, tablets, IoT devices, and more.
- Examples: ARM Cortex-A series (e.g., Cortex-A76), ARM Cortex-M series (e.g., Cortex-M4), ARM Cortex-R series.

### 3. MIPS Architecture:
- Historically used in a variety of applications, including early gaming consoles and networking equipment.
- Known for its simplicity and efficiency.
- Still used in some embedded systems and networking devices.
- Examples: MIPS32, MIPS64.

### 4. Power Architecture:
- Developed by IBM and used in various applications, including servers and embedded systems.
- Commonly found in automotive electronics and networking hardware.
- Examples: POWER9, PowerPC.

### 5. SPARC Architecture:
- Originally developed by Sun Microsystems (now Oracle).
- Commonly used in servers and high-performance computing.
- Examples: SPARC64, UltraSPARC.

### 6. Itanium Architecture:
- Developed by Intel in collaboration with Hewlett Packard (HP).
- Designed for high-performance computing and server applications.
- Itanium processors are no longer actively developed.

### 7. RISC-V Architecture:
- An open-source instruction set architecture.
- Gaining popularity in various applications due to its open nature and flexibility.
- Used in embedded systems, IoT devices, and some specialized computing tasks.

### 8. DEC Alpha Architecture:
- Developed by Digital Equipment Corporation (DEC).
- Used in workstations and servers.
- No longer actively developed or widely used.

### 9. Motorola 68k Architecture:
- Historically used in personal computers and workstations.
- Popular in the 1980s and 1990s.
- Examples: Motorola 68000 series.
123

### 10. Zilog Z80 Architecture:
- Popular in the late 1970s and 1980s, especially in home computers and embedded systems.
- Known for its simplicity and ease of use.





## Our main focus is on x86 , RISCV , ARM , CISC

### x86:- 

