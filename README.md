Context Switch Simulation with GUI
This project is a simulation of a context switch mechanism using Round-Robin (RR) scheduling in a multitasking environment. It incorporates a simple GTK-based graphical user interface (GUI) to allow user interaction with the simulation, including controlling resource occupation and release.

Features
Round-Robin Scheduling: The simulation uses Round-Robin scheduling to manage processes.
Process Control Block (PCB) Visualization: The GUI displays the state of a process before and after execution.
Resource Management: Users can simulate resource occupation and release via buttons in the GUI.
Prerequisites
To compile and run this project, ensure you have the following installed:

GCC Compiler
GTK+ 3.0
pthreads Library
File Structure
main.c: The main file containing the simulation and GUI logic.
stack_implementation.h and queue_implementation.h: Headers for stack and queue data structures used in the simulation.
process1.txt, process2.txt, process3.txt, process4.txt: Text files containing instructions for each simulated process.
