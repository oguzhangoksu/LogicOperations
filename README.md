
![Ekran görüntüsü 2024-06-28 210513](https://github.com/oguzhangoksu/LogicOperations/assets/70150316/0367a328-27c2-4705-a69e-1066c8cfeed2)

## **T**his project involves the design and implementation of a microcontroller-based system that uses an LCD display and a keypad to perform and display the results of logical operations (AND, OR, XOR, NOR) on hexadecimal numbers entered by the user. The system is developed using C programming for an 8051 microcontroller.

**Components**

- **Microcontroller**: 8051
- **LCD Display**: Used to display instructions, inputs, and results
- **Keypad**: Used to enter hexadecimal numbers and select the logical operation
- **Resistors, Capacitors, and other discrete components**: Used for interfacing and stabilization

**Functionality**

1. **User Input**:
    - The user is prompted to enter two hexadecimal numbers using the keypad.
    - Each hexadecimal number is converted to its binary representation and stored.
2. **Operation Selection**:
    - The user selects one of the logical operations (AND, OR, XOR, NOR) via the keypad.
3. **Logical Operations**:
    - The selected operation is performed on the two binary numbers.
    - The result of the operation is computed and converted back to hexadecimal for display.
4. **Output Display**:
    - The original numbers and the result of the logical operation are displayed on the LCD screen.
