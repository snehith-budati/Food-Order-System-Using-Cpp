# C++ Projects

A collection of functional console applications and utilities built in C++.

## Food Order System (food_order_system.cpp)

An interactive, terminal-based food and ice cream ordering application featuring stylized console menus, random invoice generation, persistent order history tracking, and bill computation.

### Features

- Interactive Console Interface: Beautiful ANSI colored headers and menus designed for terminal displays.
- Ice Cream & Flavour Choice: Categorized ice cream flavours (Butterscotch, Vanilla, Chocolate, Strawberry) with distinct pricing.
- Dynamic Order Customization: Enables specifying multiple items, quantities, and order modifications in real time.
- Persistent Invoicing: Automatically compiles and exports professional customer receipts to an external text file ledger (receipt.txt).
- Thread-Based Processing Effects: Utilizes chronometers and standard delay hooks to mimic transactional invoice generation steps.

### Technical Overview

- Language: C++11 or higher
- Standard Libraries: iostream, fstream, sstream, random, cstdlib, thread, chrono
- Operating System Compatibility: macOS, Linux, and POSIX-compliant terminal environments

### Compilation and Execution

Compile using any standard C++ compiler:

```bash
g++ -std=c++11 food_order_system.cpp -o food_order_system
./food_order_system
```
