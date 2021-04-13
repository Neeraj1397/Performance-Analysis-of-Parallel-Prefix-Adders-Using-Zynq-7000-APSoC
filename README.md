# Performance-Analysis-of-Parallel-Prefix-Adders-Using-Zynq-7000-APSoC
Performed a comparative study of Parallel Prefix Adders using Verilog HDL on Zynq-7000 APSoC (PL) from XIlinx. Circuits are simulated, synthesized and implemented using Vivado Design Suite. 

ABSTRACT
The heart of every processor is the Arithmetic Logic Unit (ALU) and the heart of every ALU is the Adder circuit. Adder does subtraction (via 2's complement arithmetic) and is the core part of multiplier circuits. Since addition is the most basic arithmetic operation; and adder is the most fundamental arithmetic component of the processor, over the years the field of VLSI arithmetic has been intriguing for many digital VLSI researchers around the world. Several traditional and novel approaches have been introduced as years passed by to make the addition as efficient as possible in terms of delay, power consumption, area and loading of gate outputs. This paper discusses a chosen few traditional approaches to addition, analyses their performance and then evaluates and compares the performance of several Parallel prefix adders. Parallel Prefix adders are the most efficient approach for DSP chips till date. The goal is to decide the best adder out of those discussed for a given application with low on-chip power, resource consumption and higher speed of calculation. The adders are implemented in Verilog Hardware Description Language using Vivado Design Suite wherein the designs are implemented on Xilinx ZYNQ XC7Z020 (7000 series) SoC. Subsequently, the power, delay and hardware utilization of the adders are investigated.
