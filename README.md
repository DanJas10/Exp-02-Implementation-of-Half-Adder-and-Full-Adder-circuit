# Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit

# Implementation-of-Half-Adder-and-Full-Adder-circuit
### AIM:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

### Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
Theory
Adders are digital circuits that carry out addition of numbers.

### Half Adder
Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

### Full Adder
Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin Carry = AB + ACin + BCin

 ![image](https://user-images.githubusercontent.com/36288975/163552156-a13e5a56-c638-4110-97d9-8896907c8d25.png)

#### Figure -01 HALF ADDER 


![image](https://user-images.githubusercontent.com/36288975/163552057-b3547877-6d07-45b4-b7e0-bcfebfad9e1d.png)

#### Figure -02 FULL ADDER 

### Procedure

Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.
### 
Program:
/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: Dan Jas J
RegisterNumber:  23012930
*/
Logic symbol & Truthtable
RTL realization

# CODE:

 ###  HALF ADDER:
           
![code](https://github.com/DanJas10/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150931233/3cff4712-05d3-4e0f-b73c-4913893f2d2e)

 ###  FULL ADDER:
   
![code PNG](https://github.com/DanJas10/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150931233/3e793c7a-d37d-4ba8-9f2a-62fa5389b90a)

                              


# RTL DIAGRAM:

### HALF ADDER:
 
![RTL](https://github.com/DanJas10/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150931233/d20c9c7a-c916-4ed8-bf56-e6bbda3d8377)


### FULL ADDER:

 ![RTL](https://github.com/DanJas10/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150931233/96835aca-eb7f-457b-8cc5-92e1ad8ccb13)




                                    
# TIMING DIAGRAM:

### HALF ADDER:
 
![output](https://github.com/DanJas10/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150931233/112815b5-bf3e-4b3a-8971-8e7b9ea58247)


### FULL ADDER:
 
![output](https://github.com/DanJas10/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150931233/2d93a79f-c2ca-461e-89c6-a46d6b4946f8)
 
   


# TRUTH TABLE :

### HALF ADDER:

![truth table](https://github.com/DanJas10/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150931233/f10b75d8-3c66-40dc-9d6f-723bdca8d905)



### FULL ADDER:

![truth table](https://github.com/DanJas10/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150931233/eeac2de7-7515-4a12-b507-e679b07b2657)



# Result:

 Thus,the half adder and full adder circuits are designed and the truth tables is verified using quartus software.

