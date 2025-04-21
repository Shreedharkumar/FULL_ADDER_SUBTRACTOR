**Name: SHREEDHAR KUMAR K.J**

**REGISTER NO: 212224230265**

### EX NO: 4 - FULL ADDER AND SUBTRACTOR

**AIM:**

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

**Full Adder and Full Subtractor**

**Full Adder**

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

**Figure -1 FULL ADDER**

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

**Figure -2 FULL SUBTRACTOR**

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Truthtable**

FULL ADDER

![full-adder truth table](https://github.com/user-attachments/assets/1991785f-8708-43ec-9a37-254c3c3a3eff)

FULL SUBTRACTOR

![full-subtractor truth table](https://github.com/user-attachments/assets/e9ba12e8-331d-4bd1-a543-9e51458fbea7)

**PROCEDURE**

### 1. Open Quartus Software
Launch **Quartus Prime** on your system.

### 2. Create a New Project
- Navigate to **File > New Project Wizard**.
- Set your **project directory**, **project name**, and **top-level entity name**.
- Add your **Verilog (.v)** or **VHDL (.vhd)** source file.
- Select the correct **FPGA device** based on your target board.

### 3. Add Design Code
- Open your top-level module (e.g., `main.v`).
- Paste or write your Verilog/VHDL design.

### 4. Compile the Design
- Go to **Processing > Start Compilation**.
- Wait until the compilation process is complete.
- Resolve any errors or warnings if present.

### 5. Generate RTL Schematic
- Navigate to **Tools > Netlist Viewers > RTL Viewer**.
- View the generated RTL schematic.
- Save the schematic using **File > Export** (as image or PDF).

### 6. Assign I/O Pins
- Open **Assignments > Pin Planner**.
- Assign FPGA pins to your module’s inputs and outputs.
- Click **Save** once done.

### 7. Create Waveform for Simulation
- Go to **File > New > Other Files > Vector Waveform File (.vwf)**.
- Click **Edit > Insert > Insert Node or Bus**.
- Select all input and output signals to monitor.

### 8. Set Simulation Parameters
- Define end time using **Edit > End Time** (e.g., `1 us`).
- Apply different **input combinations** on the waveform.

### 9. Run Functional Simulation
- Go to **Processing > Start Simulation**.
- The **timing diagram** (simulation output) will be displayed.

### 10. Save the Timing Diagram
- Save the waveform for future reference.
- Export the timing diagram image via **File > Export Image**.


**Program:**

FULL ADDER

![Screenshot 2025-04-17 101849](https://github.com/user-attachments/assets/6bfe6052-d3e6-4e52-948d-c1e9a512500f)

FULL  SUBTRACTOR

![Screenshot 2025-04-17 110535](https://github.com/user-attachments/assets/65852645-e920-4c86-bdd1-62efba7e979e)


**RTL Schematic**

FULL ADDER

![Screenshot 2025-04-17 101916](https://github.com/user-attachments/assets/f0c04970-051f-4743-8f8c-7be41bc62472)

FULL  SUBTRACTOR

![Screenshot 2025-04-17 110510](https://github.com/user-attachments/assets/bd8cccbe-e65b-4cac-8a7d-08c44de387d7)


**Output Timing Waveform**

FULL ADDER

![Screenshot 2025-04-17 101905](https://github.com/user-attachments/assets/aa029329-2aa8-4fb0-8666-ea4b187867c0)

FULL  SUBTRACTOR

![Screenshot 2025-04-17 110758](https://github.com/user-attachments/assets/a4411003-3628-4999-880e-7c63af923ddc)

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.
