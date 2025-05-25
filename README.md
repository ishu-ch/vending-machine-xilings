# vending-machine-xilings
Vending Machine (Verilog Project)

This project is a simple Finite State Machine (FSM) implementation of a Vending Machine using Verilog. It accepts 10, 20, and 50 unit coins and processes transitions between different cumulative amounts until the vending condition is met.
🔧 Inputs

    clk: Clock signal
    reset: Resets the machine
    coin: 2-bit input (00 for 10 units, 01 for 20 units, 10 for 50 units)

✅ Outputs

    Z: Indicates successful transaction (optional usage)
    change_given: Indicates if change is returned

💡 Functionality

    Transitions between states (S0, S10, ..., S80) based on coin input
    Dispenses product when sufficient balance is reached
    Resets automatically after transaction

📁 File(s)

    vending_machine.v – Verilog file implementing the FSM logic.

👨‍💻 Author

    Inkesh maurya

