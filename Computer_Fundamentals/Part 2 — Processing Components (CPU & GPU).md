# 02. Processing Components (CPU & GPU)

### Understanding How Computers Execute Instructions and Process Graphics

## 1. Central Processing Unit (CPU)

The **CPU (Central Processing Unit)** is the primary processor of a computer.

It executes program instructions, performs calculations, and carries out logical operations.

The CPU is commonly called the **brain of the computer** because it performs the central processing work.

### 1.1 Main Responsibilities of the CPU

- Executes program instructions.
- Performs arithmetic calculations.
- Performs logical comparisons.
- Coordinates processing activities.
- Works with memory to access the required data and instructions.

### 1.2 Main Components of a CPU

#### A. Control Unit (CU)

The Control Unit controls and coordinates the execution of instructions.

It directs how data and instructions move between different parts of the computer.

**Example:** It helps coordinate the steps required when the CPU executes an instruction.

#### B. Arithmetic Logic Unit (ALU)

The ALU performs arithmetic and logical operations.

**Arithmetic operations:**

- Addition
- Subtraction
- Multiplication
- Division

**Logical operations:**

- Greater than
- Less than
- Equal to
- AND, OR, NOT

**Example:** When a program needs to calculate `25 + 15`, the ALU performs the arithmetic operation.

#### C. Registers

Registers are very small, extremely fast storage locations inside the CPU.

They temporarily hold data, instructions, addresses, and intermediate results needed during processing.

**Example:** While the CPU is performing a calculation, registers may hold the values being used.

### Simple CPU Diagram

```text
       +----------------------+
       |         CPU          |
       |                      |
       |   +--------------+   |
       |   | Control Unit |   |
       |   +--------------+   |
       |                      |
       |   +--------------+   |
       |   |     ALU      |   |
       |   +--------------+   |
       |                      |
       |   +--------------+   |
       |   |  Registers   |   |
       |   +--------------+   |
       +----------------------+
```

**Remember:** The CPU executes instructions. The Control Unit coordinates, the ALU performs arithmetic and logical operations, and registers hold immediately needed information.

---

## 2. Graphics Processing Unit (GPU)

The **GPU (Graphics Processing Unit)** is a processor designed to handle graphics-related operations and highly parallel workloads.

It is especially useful for:

- Rendering images and graphics.
- Playing video games.
- 3D modeling and rendering.
- Video processing.
- Machine learning and other parallel computations.

### 2.1 Types of GPU

#### A. Integrated GPU

An integrated GPU is built into the CPU or processor package.

It commonly uses system RAM as graphics memory.

**Example:** Many laptops can display videos and run everyday applications without a separate graphics card.

#### B. Dedicated GPU

A dedicated GPU is a separate graphics processor, usually installed on a graphics card or integrated into a laptop as a separate GPU.

It generally has its own dedicated video memory called **VRAM**.

**Example:** A powerful gaming laptop may have a dedicated NVIDIA or AMD GPU.

### Integrated vs. Dedicated GPU

| Integrated GPU | Dedicated GPU |
|---|---|
| Built into the processor package | Separate graphics processor |
| Usually uses system RAM | Usually has dedicated VRAM |
| Generally consumes less power | Often consumes more power |
| Suitable for everyday graphics tasks | Better suited to demanding graphics workloads |

**Remember:** A dedicated GPU is not mandatory for every computer. Many computers have integrated graphics that are sufficient for everyday use.

---

## 3. CPU vs. GPU

| CPU | GPU |
|---|---|
| General-purpose processor | Specialized graphics and parallel processor |
| Executes a wide variety of instructions | Handles many parallel operations efficiently |
| Runs general program logic | Commonly handles graphics and demanding parallel workloads |

### How They Work Together

The CPU and GPU can work together when running an application.

For example, when playing a video game:

1. The CPU executes game logic and coordinates tasks.
2. The GPU processes graphics-related workloads.
3. The monitor displays the rendered frames.

---

## 4. Key Takeaways

- CPU stands for Central Processing Unit.
- The CPU executes program instructions.
- The Control Unit coordinates instruction execution.
- The ALU performs arithmetic and logical operations.
- Registers hold immediately needed information inside the CPU.
- GPU stands for Graphics Processing Unit.
- GPUs are designed for graphics and highly parallel workloads.
- Integrated GPUs are built into the processor package.
- Dedicated GPUs are separate graphics processors and generally have dedicated VRAM.
- Not every computer needs a dedicated GPU.

### Quick Review

| Component | Main Function |
|---|---|
| CPU | Executes program instructions |
| Control Unit | Coordinates instruction execution |
| ALU | Performs arithmetic and logical operations |
| Registers | Hold immediately needed CPU data |
| GPU | Handles graphics and parallel processing |
| VRAM | Video memory used by a GPU |

---

*Computer Fundamentals | Beginner Level*

