# EXPERIMENT:01 ALP FOR 8086
```
Name : Someasvar R
Roll no : 212221230103
Date of experiment :
```




## Aim: 
To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 
```
8086  emulator
```
## Theory :
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







## Programs for arithmetic  operations:

## Addition  of 8 bit ALP:
```
org 100h
mov AX, 74H;
mov BX, 20H;
ADD AX,BX
HLT
ret


```

## Output:
![image](https://github.com/SOMEASVAR/EXPERIMENT--01-ALP-FOR-8086/assets/93434149/6dcf801f-a327-47a6-9fee-65528862205e)


 
## Subtraction   of 8 bit numbers  ALP:
```
org 100h
mov AX, 24H;
mov BX, 20H;
SUB AX,BX
HLT
ret
```
 
## Output:
![image](https://github.com/SOMEASVAR/EXPERIMENT--01-ALP-FOR-8086/assets/93434149/09c992d3-f7ae-477e-8ae1-46c159ed4115)




## Multiplication alp:
```
org 100h
mov AL, 70H;
mov BL, 52H;
MUL BL
HLT
ret
```
## Output :
![image](https://github.com/SOMEASVAR/EXPERIMENT--01-ALP-FOR-8086/assets/93434149/6d07213f-54f3-4b36-99a7-67455f6ac769)



## Division alp:
```
org 100h
mov AL, 70H;
mov BL, 52H;
DIV BL
HLT
ret
```

## Output:
![image](https://github.com/SOMEASVAR/EXPERIMENT--01-ALP-FOR-8086/assets/93434149/ebaeb264-7d41-4863-af21-8756868bd99d)
## AND Operation:
```
org 100h
mov AH, 12H
mov BH, 45H
AND AH,BH
HLT
ret

```
## Output:
![image](https://github.com/SOMEASVAR/EXPERIMENT--01-ALP-FOR-8086/assets/93434149/2b690851-6052-424e-a517-c9ca7302b841)

## OR Operation:
```
org 100h
mov AH, 56H
mov BH, 67H
OR AH, BH
HLT
ret
```
## Output:
![image](https://github.com/SOMEASVAR/EXPERIMENT--01-ALP-FOR-8086/assets/93434149/edb98527-89fc-40c3-8cf8-66d526d9b3ac)
## NOT Operation:
```
org 100h
mov AX, 123H
NOT AX
HLT
ret
```
## Output:
![image](https://github.com/SOMEASVAR/EXPERIMENT--01-ALP-FOR-8086/assets/93434149/a94c40af-8cf5-4101-8ae3-ba66496567b1)
## XOR Operation:
```
org 100h
mov AL, 99H
mov BL, 88H
XOR AL,BL
HLT
ret

```
## Output:
![image](https://github.com/SOMEASVAR/EXPERIMENT--01-ALP-FOR-8086/assets/93434149/ae99e515-ae51-4d02-9022-a9ca5da469a0)



## Result :
Thus, a program is executed on ALP for the fundamental arithmetic and logical operations successfully.








