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
org 100h
MOV al,11h;
MOV bl,20h;
ADD al,bl;
MOV [6379h],al;
ret
```
## Output  
 ![PMC_1 1](https://github.com/gummadileepkumar/EXPERIMENT--01-ALP-FOR-8086/assets/118707761/794de7db-ae43-44a6-89b7-1dca2afeade0)

 
## Subtraction of 8 bit ALP
```python
org 100h
MOV al,20h;
MOV bl,[8778h];
SUB bl,al;
MOV [8798h],bl;
ret
```
## Output
![PMC_1 2](https://github.com/gummadileepkumar/EXPERIMENT--01-ALP-FOR-8086/assets/118707761/246ab351-f7a0-4af6-900f-254cb03e2e45)


## Multiplication ALP
```python
org 100h
MOV al,13h;
MOV bl,2h;
MUL bl;
MOV [6063h],bl;
ret
```
 ## Output  
![PMC_1 3](https://github.com/gummadileepkumar/EXPERIMENT--01-ALP-FOR-8086/assets/118707761/f9185e67-7762-401a-98e8-352e32d4c86d)


## Division ALP
```python
org 100h
MOV al,26h;
MOV bl,[2369h];
DIV bl;
MOV [2399h],al;
ret
```
## Output  
![PMC_1 4](https://github.com/gummadileepkumar/EXPERIMENT--01-ALP-FOR-8086/assets/118707761/be699045-32fc-40ef-80ab-2c6a61a2f477)


## Programs for logical  operations

## AND
```python
org 100h
MOV bx,1000h;
AND bx,1111h;
MOV [0040h+02],bx;
ret
```
## Output 
![PMC_1 5](https://github.com/gummadileepkumar/EXPERIMENT--01-ALP-FOR-8086/assets/118707761/44a5726a-01ae-4468-ad33-0ca505204a98)


## OR
```python
org 100h
MOV ax,[0070h];
MOV bx,1000h;
OR ax,bx;
MOV [0060h],ax;
ret
```
## Output
![PMC_1 6](https://github.com/gummadileepkumar/EXPERIMENT--01-ALP-FOR-8086/assets/118707761/356a216e-a9f8-41b7-8c09-540a43467ff5)


## NOT
```python
org 100h
MOV bx,0060h;
MOV ax,[bx]; 
NOT al;
MOV [0060h+04],ax;
ret
```
## Output

![PMC_1 7](https://github.com/gummadileepkumar/EXPERIMENT--01-ALP-FOR-8086/assets/118707761/cc96dc8a-031a-4f02-827d-12fbade9af48)

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








