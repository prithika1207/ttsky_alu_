<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

# ALU (Arithmetic Logic Unit)

## What is ALU?
The ALU is a part of the CPU that performs mathematical and logical operations.

## What it does
- Adds numbers
- Subtracts numbers
- Performs logic operations (AND, OR, NOT)
- Compares values

## How it works (simple)
- Takes two inputs (numbers in binary)
- Gets a command from the CPU (like ADD or AND)
- Performs the operation
- Sends the result back

## Example
A = 5, B = 3  
Command = ADD  
Result = 8

## Why it is important
- It helps the computer do all calculations
- It is essential for running programs

## How to test

# ALU Testing (Arithmetic Logic Unit)

## What is ALU testing?
ALU testing means checking if the ALU gives correct results for all operations like addition, subtraction, and logic gates.

## How to test ALU

### 1. Give inputs
Provide two numbers (A and B), usually in binary or decimal.

Example:
A = 2  
B = 3  

---

### 2. Select operation
Choose the operation using control signals:
- ADD
- SUB
- AND
- OR

---

### 3. Check output
Compare ALU output with expected result.

Example:
A = 2, B = 3  
Operation = ADD  
Expected result = 5  

---

### 4. Test different cases
- Small numbers (1, 2, 3)
- Zero values (0 + 0)
- Large numbers
- Edge cases (overflow situations)

---

## Simple idea
Input → Operation → Output → Verify result

---

## Goal of testing
To make sure ALU works correctly for all arithmetic and logic operations.

## External hardware

no external hardwre
