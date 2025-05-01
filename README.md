# Mon: My 4-bit CPU

Made from Scratch by [Pranav Verma](https://pranavv.co.in).

## Parts List (Tentative)

### 🔌 Power & Basics
- [ ] 1x 5V Regulated Power Supply / Battery Pack  
- [ ] 2–3x Breadboards (Full size)  
- [ ] Jumper Wires (Male-to-Male, Male-to-Female, Assorted)  
- [ ] Resistors (100Ω, 330Ω, 1kΩ, 10kΩ – Assorted pack)  
- [ ] Capacitors (10nF, 100nF – for decoupling)  
- [ ] Push Buttons (2–4 pcs for manual input/reset)  
- [ ] LEDs (20+ pcs, Red/Green/Yellow/Blue)  

---

### 🧠 Core ICs

#### ⏱️ Clock Generation
- [ ] 1x NE555 Timer (for adjustable clock pulses)  
- [ ] 1x 100kΩ potentiometer (for clock speed control)  

#### 🧮 Arithmetic & Registers
- [ ] 1x 74LS181 – 4-bit ALU  
- [ ] 1x 74LS161 – 4-bit synchronous binary counter (Program Counter)  
- [ ] 3–4x 74LS173 – 4-bit register (Instruction Register, Accumulator, Output Register)  

#### 🧠 Memory
- [ ] 2x 74LS189 – 4x16 RAM (for small RAM)  
_or_  
- [ ] 1x 28C16 EEPROM (requires USB EEPROM programmer)  

#### 🧭 Control & Logic
- [ ] 1x 74LS138 – 3-to-8 line decoder (Instruction decoding)  
- [ ] 1x 74LS157 – 4-bit 2:1 multiplexer  
- [ ] 2–3x 74LS245 or 74LS244 – Octal bus transceiver (for data bus buffering)  

#### 🔗 Logic Gates
- [ ] 1x 74LS00 – Quad 2-input NAND gates  
- [ ] 1x 74LS08 – Quad 2-input AND gates  
- [ ] 1x 74LS32 – Quad 2-input OR gates  
- [ ] 1x 74LS04 – Hex Inverter (NOT gates)  

---

### 🖥️ Output Display
- [ ] 8x LEDs (for output register)  
- [ ] 8x 330Ω resistors (for LED current limiting)

---

### 🔧 Optional / Helpful Extras
- [ ] 1x USB EEPROM Programmer (for 28C16 or similar)  
- [ ] 1x 74LS14 – Schmitt Trigger inverter (for button debouncing)  
- [ ] 1x 74LS373 – Transparent latch (optional, for address bus control)  
- [ ] Oscilloscope (even basic like DSO138) – **optional but useful**
