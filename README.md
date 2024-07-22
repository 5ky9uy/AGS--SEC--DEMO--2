# SCHEDULE 
* 20h remaining
* Expected by July 28, 2024
  
# DESCRIPTION
* Verilog-based IC-layer HW-trojan demonstration for C140.

# COMPONENTS
* 4-bit Digital Lock
* Lock-bypassing HW-trojan injection (if trojan activates, then the lock bypasses key if submission has a '1' bit in the 1st position).

# TOOLS
* Verilog
* Pencil/Paper
* Xilinx Vivado (on AWS Windows 11 Workspace intance)
* EDA Playground (for prototyping and demonstration of wave analysis triggered by testbench)
* Markdown (docs)
* Pages (diagrams)

# STEPS
1. Handwrite original Digital Lock logic. 
2. Simplify Digital Lock logic using Karnaugh Map. 
3. Write original Digital Logic in Verilog. 
4. Demonstrate the HW-trojan in action by showing how it can leak the passkey to a connected peripheral device given a different input.
5. Explain other advanced injection methods (e.g. using photoresistant ion-based doping mask phase of fabrication to sneakily increase required voltage thresholds between specified benign pre-existing or added circuits by creating vacancies for positive flow or adding electrons for negative flow, allowing the activation of the trojan by passing a custom voltage).
6. Explain pre and post injection mitigations now and in the future (e.g. NVC Quantum Sensor for precise electromagnetic difference scanning).

# REFERENCES
1. https://ryancor.medium.com/hardware-trojans-under-a-microscope-bf542acbcc29 
