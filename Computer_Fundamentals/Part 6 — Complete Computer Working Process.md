# 06. Complete Computer Working Process

### Understanding How a Computer Starts and Runs Applications

Now let's connect everything we have learned.

Imagine pressing the power button on your laptop and opening Google Chrome.

What happens inside the computer?

Let's understand the complete process step by step.

---

## 1. Step 1: Power Supply

When you press the power button, the computer's power circuitry starts the power-on process.

The PSU in a desktop or the power adapter and internal power circuitry in a laptop provide the required electrical power.

---

## 2. Step 2: Firmware Starts

The system firmware, such as **UEFI**, begins executing its startup instructions.

It initializes essential hardware and performs startup checks.

This early startup process includes the **Power-On Self-Test (POST)**.

---

## 3. Step 3: Operating System Booting

After hardware initialization, the firmware identifies a bootable device and starts the bootloader or operating system boot process.

The operating system's required components are loaded from storage, such as an SSD, into RAM.

---

## 4. Step 4: CPU Executes Instructions

The CPU executes the instructions required to initialize and run the operating system.

It works with RAM and cache to access the data and instructions it needs.

---

## 5. Step 5: Operating System Becomes Ready

The operating system initializes its services, manages hardware resources, and provides the environment in which applications can run.

For example, Windows displays the desktop and becomes ready for use.

---

## 6. Step 6: Opening Google Chrome

Now you click the Chrome icon.

1. Chrome's installed program files are stored on the SSD.
2. The operating system loads the required parts of Chrome into RAM.
3. The CPU executes Chrome's instructions.
4. Cache helps the CPU access useful data and instructions faster.
5. The GPU may help render the interface.
6. The monitor displays the Chrome window.

---

## 7. Complete Computer Working Process

```text
        POWER BUTTON
             |
             v
       POWER CIRCUITRY
             |
             v
        FIRMWARE (UEFI)
             |
             v
      HARDWARE INITIALIZATION
             |
             v
      OPERATING SYSTEM BOOT
             |
             v
        SSD  --->  RAM
             |
             v
       CPU EXECUTES
        INSTRUCTIONS
             |
             v
       APPLICATION RUNS
             |
             v
        OUTPUT DISPLAY
```

---

## 8. Understanding the Role of Each Component

This is especially important:

- **SSD:** Stores the operating system, applications, and personal files permanently.
- **RAM:** Temporarily holds the data and instructions needed by running programs.
- **CPU:** Executes the instructions.
- **Cache:** Helps the CPU access frequently or recently needed information faster.
- **GPU:** May help process and render graphics.
- **Motherboard:** Provides connections and communication pathways between components.
- **PSU / Power Circuitry:** Supplies the electrical power required by the system.
- **Cooling System:** Helps maintain safe operating temperatures.
- **Operating System:** Manages hardware resources and provides the environment for applications.

### Real-Life Example: Opening Google Chrome

Even if you shut down your laptop, Google Chrome's installed files remain on the SSD.

When you start Chrome again:

1. The operating system accesses the application files on the SSD.
2. It loads the necessary parts into RAM.
3. The CPU executes Chrome's instructions.
4. Cache may provide faster access to useful data and instructions.
5. The GPU may assist with rendering.
6. The monitor displays the application.

> **Important:** SSD → RAM → CPU is a useful simplified learning model. Real computer data movement is more complex: the CPU, memory controller, cache hierarchy, and operating system coordinate many transfers.

---

## 9. Key Takeaways

- Pressing the power button starts the computer's power-on process.
- Firmware such as UEFI initializes hardware and begins the boot process.
- POST is part of the early startup checks.
- The operating system is loaded from storage into RAM during booting.
- The CPU executes the instructions required to run the operating system.
- The operating system manages hardware resources and provides an environment for applications.
- When an application opens, its necessary parts are loaded into RAM.
- The CPU executes application instructions.
- Cache helps the CPU access useful information faster.
- The GPU may help render graphics.
- Output devices present the result to the user.

### The Basic Computer Working Model

```text
POWER
  |
  v
FIRMWARE
  |
  v
OS BOOT
  |
  v
RAM + CPU
  |
  v
APPLICATION
  |
  v
OUTPUT
```

### The Most Important Storage and Processing Distinction

```text
SSD   = Stores files and applications
RAM   = Holds active working data
CACHE = Helps CPU access useful data faster
CPU   = Executes instructions
GPU   = Handles graphics and parallel workloads
```

---

*Computer Fundamentals | Beginner Level*


