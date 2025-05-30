
# 4-Bit Comparator & Max Number Selector Using Logic Gates (Hardware Project)

## 📘 Project Overview

This is a **Digital Logic Design (DLD)** hardware project where I built a **4-bit comparator** using basic logic gates (**AND, OR, NOT, XOR**) on a breadboard. The project compares two 4-bit binary numbers, determines if one is greater than the other, and displays the **larger number using a multiplexer (MUX)**.

---

## 🧠 Project Description

The circuit compares two 4-bit numbers:

* `A = A4 A3 A2 A1`
* `B = B4 B3 B2 B1`

It determines whether **A > B** and uses a **MUX** to display the larger of the two numbers.

### 🔧 Logic Used:

* **XOR Gates**: Check if bits are different.
* **AND + NOT Gates**: Used to determine which bits are greater.
* **Cascading Comparison**: Bitwise comparison starts from MSB to LSB.
* **MUX**: Displays the greater 4-bit number based on comparison result.

The comparator logic is implemented using discrete ICs on a breadboard.

---

## 🔩 Hardware Components

* Breadboard
* Power supply (5V)
* Logic Gate ICs:

  * **7408** (AND)
  * **7432** (OR)
  * **7486** (XOR)
  * **7404** (NOT)
* **74157**  MUX
* LEDs (for output display)
* Input switches (for binary inputs)
* Connecting wires

---

## ⚙️ How It Works

1. The circuit takes two 4-bit inputs: A and B.
2. Using gate-level logic, it compares each bit from MSB to LSB.
3. If A > B, the MUX selects and displays A.
4. If A ≤ B, the MUX selects and displays B.
5. Output is shown using LEDs.

---

## 🧪 Testing Procedure

1. Connect inputs using DIP switches.
2. Observe comparison output via an indicator LED (A > B).
3. The selected number (A or B) is shown on 4 output LEDs.
4. Test all possible input combinations to verify correctness.

---

## ✅ Learning Outcomes

* Hands-on experience designing digital circuits using hardware.
* Practical application of gate-level binary comparison.
* Understanding of MUX operation and control logic.
* Improved skills in circuit debugging and layout.

---

## 👨‍🎓 Author

**\[Shiva Prasad Sarkar]**
DLD Hardware Project – \[Spring 2025]
Instructor: \[Towshik Anam Taj (TWK)]

---


