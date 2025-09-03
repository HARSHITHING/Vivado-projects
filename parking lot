# Vivado-projects
Parking Lot Occupancy Counter
 Project Overview.
This project implements a digital logic circuit in Verilog to accurately track the number of occupied slots in a parking lot. It is designed to be a robust, hardware-based solution that prevents the common errors associated with manual or software-only tracking systems, such as incorrect counts due to human error or data synchronization issues.

 Problem Statement: Manual or simplistic counting systems in parking lots are often unreliable. They can lead to inaccurate occupancy information, causing driver frustration and inefficient use of parking spaces. The goal of this project is to provide a precise, real-time count using a dedicated hardware counter. 

Solution: The solution is a synchronous digital counter designed in Verilog. It handles incoming and outgoing vehicles by incrementing and decrementing a count. Key features of the design include:
-Scalability: The counter's parameters (NUM_SLOTS, COUNTER_WIDTH) can be easily adjusted to accommodate different parking lot sizes. 
-Overflow Prevention: The counter will not increment if the number of cars reaches the maximum defined slots.
-Underflow Prevention: The counter will not decrement if the number of cars is already zero.

Project Files :

 parking_counter.v: The main module containing the core counter logic. This is the synthesizable design that would be implemented on an FPGA or ASIC. It includes inputs for clock, reset, car entry, and car exit, and an output for the current occupancy count.  

parking_counter_tb.v: The testbench module for simulating and verifying the parking_counter.v design. It provides a sequence of input signals to test various scenarios, such as multiple cars entering and leaving, and checks for correct overflow and underflow behavior.

 How to Run the Testbench:  To verify the functionality of the design, you can run the testbench in any Verilog simulator, such as Vivado's XSim, ModelSim, or Icarus Verilog. The testbench will simulate the clock and input signals and display the counter's value at each step.

1. Compile both parking_counter.v and parking_counter_tb.v.
2. Start the simulation with parking_counter_tb as the top-level module. 
3. Observe the output in the console for the simulation log, which tracks the count at different time intervals.


Tags: #Verilog #FPGA #HardwareDesign #DigitalLogic #Engineering
