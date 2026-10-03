# 8051 MiniRTOS

## Project Overview

A hands-on project to understand and implement core **Real-Time Operating System (RTOS) concepts** using the 8051 microcontroller architecture.

The project focuses on task scheduling, context switching, interrupts, timers, task management, and synchronization through simulations and progressively developed firmware.

**Primary Goal:** Build a strong foundation in RTOS design and firmware development, focusing on scheduling and kernel mechanisms rather than processor architecture.

---

## Objectives

- Understand the fundamentals of real-time operating systems.
- Explore cooperative and preemptive scheduling.
- Implement and simulate scheduling algorithms.
- Understand task control blocks (TCBs) and task states.
- Explore timers, interrupts, and context switching.
- Implement basic RTOS services.
- Evaluate scheduling behavior, timing, and resource usage.

---

## Project Phases

### Phase 1: RTOS Fundamentals

- Understand real-time systems and RTOS architecture.
- Study tasks, processes, threads, and scheduling.
- Explore task states and scheduling policies.

**Outcome:** A conceptual understanding of RTOS fundamentals.

### Phase 2: Scheduling Simulation

- Implement FCFS, Round Robin, and priority scheduling in Python.
- Simulate multiple tasks with different execution times and priorities.
- Analyze waiting time, response time, and turnaround time.

**Outcome:** A working scheduler simulator.

### Phase 3: 8051 Fundamentals for RTOS

- Learn the 8051 registers, memory organization, stack, and instruction set as needed.
- Explore timers, interrupts, and basic assembly programs using EdSim51.
- Understand the hardware mechanisms needed for task scheduling.

**Outcome:** Familiarity with the 8051 features required for RTOS development.

### Phase 4: RTOS Kernel Design

- Design task control blocks.
- Implement task states and task management.
- Explore delays, periodic execution, and task priorities.
- Study context switching and stack management.

**Outcome:** A basic RTOS kernel design.

### Phase 5: Firmware Implementation

- Implement core scheduling mechanisms using 8051-compatible C and assembly.
- Explore cooperative context switching.
- Investigate timer-driven preemption and interrupt-based scheduling.
- Integrate basic RTOS services.

**Outcome:** A minimal RTOS firmware implementation, subject to toolchain and simulator support.

### Phase 6: Testing and Validation

- Test scheduling behavior with multiple tasks.
- Examine timing and task execution order.
- Investigate context-switching overhead and stack usage.
- Document limitations and possible improvements.

**Outcome:** A tested and documented RTOS prototype.

---

## Tools and Technologies

- **Python:** Scheduler simulation and testing.
- **EdSim51:** 8051 assembly, timers, and interrupt experiments.
- **C / 8051 Assembly:** Firmware and kernel implementation.
- **Online compilers and simulators:** Browser-based development where supported.
- **Git and GitHub:** Version control and project documentation.

---

## Non-Goals

- Building a production-ready RTOS.
- Developing a complete 8051 emulator.
- Deep exploration of processor architecture.
- Implementing advanced memory protection or multiprocessing.
- Requiring physical hardware.

---

## Expected Outcome

A small educational RTOS prototype and a collection of simulations and experiments demonstrating fundamental RTOS concepts, with an emphasis on scheduling, task management, context switching, and firmware-level execution.

---

## Repository Structure

```text
8051-MiniRTOS/
│
├── README.md
├── PROJECT_SCOPE.md
├── docs/
│   ├── rtos_fundamentals.md
│   ├── scheduling.md
│   └── design.md
│
├── simulations/
│   ├── fcfs.py
│   ├── round_robin.py
│   └── priority.py
│
├── firmware/
│   ├── kernel/
│   ├── tasks/
│   └── drivers/
│
├── tests/
│
└── logs/
```

*The repository structure is provisional and will evolve as the project progresses.*
