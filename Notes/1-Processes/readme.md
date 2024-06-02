# PART A: Processes

## Introduction to operating systems

- A running program does one very simple thing: it executes in- structions. Many millions (and these days, even billions) of times every second, the processor **fetches** an instruction from memory, **decodes** it (i.e., figures out which instruction this is), and **executes** it (i.e., it does the thing that it is supposed to do, like add two numbers together, access memory, check a condition, jump to a function, and so forth). After it is done with this instruction, the processor moves on to the next instruction, and so on, and so on, until the program finally completes. This is also Von Neumann model of computing.
- There is a body of software responsible for making easy to run programs, called the operating system (OS), as it is in charge of making sure the system operates correctly and efficiently in an easy-to-use manner.
- The primary way the OS does this is through a general technique that we call virtualization
- OS takes a physical resource (such as the processor, or memory, or a disk) and transforms it into a more gen- eral, powerful, and easy-to-use virtual form of itself
- OS is also called **virtual machine** due to this reason.
