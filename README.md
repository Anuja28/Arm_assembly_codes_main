# Arm_assembly_codes_main
Question no 4:
===No you can not create nested if else loop in assembly language since there is no conditional checking done ITE as APSR is not affected by the ITE statement
Question no 5:
====Using keyboard interfacing with STM32--A matrix keypad can be interfaced to the discovery board.
Then, an infinite while loop can be used to scan for a key press. When the key press is detected, the digit entered can be identified using the in port of the board(by corresponding ASCII code)
Once the digit is been identified,the same logic in question 3can be implemented to find whether the number is even or odd.
Similarly other sensors can also be used to to find the digit entered by connecting them to i/o ports of the board with the help of the push buttons. 
