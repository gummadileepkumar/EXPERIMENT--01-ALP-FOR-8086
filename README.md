# EXPERIMENT--01-ALP-FOR-8086
### Name : Gumma Dileep Kumar
### Roll no : 212222240032
### Date of experiment :





## Aim: To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 8086  emulator 
## Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.


 ## Running the Emulator :
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
2.	  Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color 
 
 
3.		write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 

4.	 Compile the program and check for the errors 
5.	Run (once there is no syntax error) 

6.	Click OK to see/view the output of your program on the Emulator screen. 


7.	After running the program, another menu screen will be displayed, where you have the option to “View” symbol table,
8.	 


![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)











9.	Click on emulate to start emulation 








![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)








10.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below 






![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)







## Programs for arithmetic  operations

## Addition of 8 bit ALP  
```python
Mov AL,74H
Mov BL,69H
Add AL,BL
HLT
```
## Output  
 
![Addition](https://github.com/gummadileepkumar/EXPERIMENT--01-ALP-FOR-8086/assets/118707761/5f44a6c1-d56d-49ef-b0f9-a676ba1958e4)

 
## Subtraction of 8 bit ALP
```python
Mov AL,84H
Mov BL,63H
Sub AL,BL
HLT
```
## Output
![Subtraction](https://github.com/gummadileepkumar/EXPERIMENT--01-ALP-FOR-8086/assets/118707761/76414450-d504-4abe-a5be-7b307cbcab90)




## Multiplication ALP
```python

org 100h
MOV AL,75H
MOV BL,32H
MUL AL,BL
HLT

ret
```
 ## Output  

![Multi](https://github.com/gummadileepkumar/EXPERIMENT--01-ALP-FOR-8086/assets/118707761/5f32e482-1059-4910-a854-c64f4ff3ba37)


## Division ALP
```python

org 100h
MOV AL,68H
MOV BL,18H
DIV AL,BL
HLT

ret
```
## Output  
![Divi](https://github.com/gummadileepkumar/EXPERIMENT--01-ALP-FOR-8086/assets/118707761/db17ab75-0e97-4f1f-95c0-8b7c095ae0a5)



## Programs for logical  operations

## AND
```python
Mov AL,33H
Mov BL,44H
AND AL,BL
HLT
```
## Output 
![AND_operation](https://github.com/gummadileepkumar/EXPERIMENT--01-ALP-FOR-8086/assets/118707761/2d0ef273-3047-406d-9254-260b3ceb2c65)



## OR
```python
Mov AL,45H
Mov BL,66H
OR AL,BL
HLT
```
## Output
![OR_Operation](https://github.com/gummadileepkumar/EXPERIMENT--01-ALP-FOR-8086/assets/118707761/91fdce70-6088-4e6b-b43f-49d929f4d0ca)



## NOT
```python
Mov AL,65H
NOT AL
HLT


```
## Output

![NOT_Operation](https://github.com/gummadileepkumar/EXPERIMENT--01-ALP-FOR-8086/assets/118707761/bae841d8-499f-46f7-a221-e994de1be223)


## XOR
```python
org 100h
MOV bx,0050h;
MOV ax,[bx]; 
XOR ax,bx;
MOV [0050h+03],ax;
ret
```
## Output
![PMC_1 8](https://github.com/gummadileepkumar/EXPERIMENT--01-ALP-FOR-8086/assets/118707761/f4251ca4-5d65-49cd-a824-efa6e8579359)


## Result :
Thus, ALP for fundamental arithmetic and logical operations are executed successfully.








