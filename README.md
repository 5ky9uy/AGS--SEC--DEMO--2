# SCHEDULE 
* 20h remaining
* Expected by July 28, 2024
  
# DESCRIPTION
* Verilog-based HW-trojan demonstration for C140. 

# COMPONENTS
* 4-bit Digital Lock (with injected lock-bypassing HW-trojan; if trojan activates, then the lock bypasses key if submission has a '1' bit in the 1st position). 

# TOOLS
* Verilog
* Pencil/Paper
* Xilinx Vivado (on AWS Windows 11 Workspace intance)
* EDA Playground (for prototyping and demonstration of wave analysis triggered by testbench)

# STEPS
1. Handwrite original Digital Lock logic. 
2. Simplify Digital Lock logic using Karnaugh Map. 
3. Write original Digital Logic in Verilog. 
4. Demonstrate the HW-trojan in action by showing how it can leak the passkey to a connected peripheral device given a different input.
5. Explain pre and post injection mitigations (current or future -- NVC Quantum Sensor for precise electromagnetic difference scanning).
