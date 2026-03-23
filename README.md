**📘 4-bit ALU (Arithmetic Logic Unit) – Verilog**

**🔷 Project Overview**

 This project implements a 4-bit Arithmetic Logic Unit (ALU) using Verilog HDL in Xilinx Vivado.
 
 An ALU performs multiple arithmetic and logical operations based on a select signal, making it a key component in digital systems and processors.
 
**🎯 Objective**

 Design a 4-bit ALU
 
 Perform arithmetic and logical operations
 
 Verify functionality using simulation
 
**⚙️ Inputs & Outputs**

**🔹 Inputs:**

 a [3:0] : First operand

 b [3:0] : Second operand

 sel [1:0] : Operation select

**🔹 Outputs:**

 result [3:0] : Output of operation
 
 cout : Carry/borrow output
 
**🧠 Operations Performed**

sel           Operation

00          Addition (a + b)

01          Subtraction (a - b)

10          AND (a & b)

11          OR (a | b)

**Testbench Summary**

 Applied different values of a and b

 Changed sel to test all operations

 Verified output using waveform simulation
 
 <img width="1919" height="1017" alt="WAVEFORM" src="https://github.com/user-attachments/assets/64a619ca-2df0-4b3b-a748-2b3a5daf5947" />

**📊 Sample Results**

**a          b        sel        Operation       Result**

  0101     0011       00          ADD            1000
  
  0101     0011       01          SUB            0010
  
  0101     0011       10          AND            0001
  
  0101     0011       11          OR             0111
  
**🛠 Tools Used**

💻 Xilinx Vivado

🔤 Verilog HDL

**🚀 Applications**

 Microprocessors
 
 Digital signal processing
 
 Embedded systems
 
 FPGA-based designs
 
**📌 Conclusion**

The 4-bit ALU integrates multiple operations into a single unit, demonstrating a fundamental building block of modern computing systems.

**👨‍💻 Author**

Shiv Balaram N

B.E Electronics and Communication Engineering
