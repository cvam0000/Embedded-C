# Embedded-C
### REGISTER

- collection of some bits (8 bits in case of 8bit MCUs).
- Either each different bit in a register has some purpose or the register as a  holds a value. 
- Registers works  as connection between a CPU and a Peripheral device (like ADC or TIMER). 
- By changing the value of  the register the CPU is actually instructing the PERIPHERAL to do something or it is configuring it in some way.
- And by reading a register,The CPU can know the state of peripheral or read associated data.


<p align="center">
  <img src="https://raw.githubusercontent.com/cvam0000/Embedded-C/master/assest/register.png" width="550" title="">
  
</p>

- configure and command the peripheral 

- transfer the data 


<p align="center">
  <img src="https://raw.githubusercontent.com/cvam0000/Embedded-C/master/assest/reg.png" width="550" title="">
  
</p>

- Get the status and data from peripheral 

### BINARY , HEXADECIMAL  NO IN C 
Most of the time we are not interested in the  value of the variable but the state of the register .

`// if we declare a variable to store the state of register eg `

`// int reg = 10101010;`

`// compiler intruppt 10101010 as decimal no `

`// we have to do this like int reg = 0b101010101 and reg=0x10101010`

 `ob for binary ox for hexadecimal`
