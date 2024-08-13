# Kernel Modules Internship Tasks

This repository contains a series of Linux kernel module projects developed as part of an internship program focused on kernel development. Each submodule represents a different task, designed to demonstrate various aspects of kernel module programming, from basic logging to advanced data structures and debug interfaces.
Submodules Overview

    hello_kernelcare:
        Task: Create a simple kernel module that logs "Hello, KernelCare!" upon loading and "Goodbye, KernelCare!" upon unloading.
        Objective: Demonstrate basic kernel module operations and integration with the kernel's logging system.

    kernelcare_debug_module:
        Task: Extend the basic module to create a debugfs subdirectory called "kernelcare" with two files: jiffies (read-only) and data (read/write with mutex protection).
        Objective: Showcase usage of debugfs, synchronization mechanisms, and secure data handling in kernel space.

    kernel_identity_manager:
        Task: Implement a linked list structure within the kernel to manage "identity" structures, with functionalities like creation, lookup, hiring, and deletion.
        Objective: Explore kernel data structures, specifically linked lists, and how to manage complex data within the kernel.

## Building and Testing

Each submodule includes its own README file with detailed instructions for building and testing the kernel module. Ensure that you have the appropriate kernel headers installed and the necessary development tools before attempting to build any of the modules.

## License

All projects are licensed under the GPL v2 license, as indicated by the module source file headers.