**# barrel-shifter using verilog**

A barrel shifter is a digital circuit that can shift a data word by a specified number of bits without using multiple sequential shift operations. It is often used in high-speed computing applications for its efficiency in shifting operations.


**Inputs:**

data_in: The 4-bit input data that needs to be shifted.

shift: A 2-bit value that specifies the number of positions to shift.

left_right: A control signal to determine the direction of the shift (0 for left shift, 1 for right shift).

**Outputs:**

data_out: The 4-bit output data after the shift operation.

Left Shift:

When left_right is 0, the data is shifted to the left based on the shift value.
For example, if the shift is 2'b01, the input data_in is shifted left by 1 position.

Right Shift:

When left_right is 1, the data is shifted to the right based on the shift value.
For example, if the shift is 2'b10, the input data_in is shifted right by 2 positions.


![7MKFU](https://github.com/panda12384/barrel-shifter/assets/160568759/1a845ca3-7c6a-47b6-9f2b-f33aa062d064)



**The Output**


![Screenshot 2024-07-05 142642](https://github.com/panda12384/barrel-shifter/assets/160568759/52f432c1-a629-449d-948d-b289c9fe538c)
