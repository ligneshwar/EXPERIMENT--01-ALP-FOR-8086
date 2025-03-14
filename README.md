# EXPERIMENT--01-ALP-FOR-8086
```
Name :Ligneshwar K
Roll no :212223230113
Date of experiment : 14/03/2025
```
## Aim: 
To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 
8086  emulator 
## Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.


 ## Running the Emulator :
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
2. Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color  
3.	write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 
4.	 Compile the program and check for the errors 
5.	Run (once there is no syntax error) 

6.	Click OK to see/view the output of your program on the Emulator screen. 


7.	After running the program, another menu screen will be displayed, where you have the option to “View” symbol table,
    
![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)

9.	Click on emulate to start emulation 

![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)

10.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below 

![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)

## Programs for arithmetic  operations:

## Addition  of 8 bit ALP:
```
mov AL,74H
mov BL,69H
ADD AL,BL
HLT
```
## Output :
![add_8bit](https://github.com/user-attachments/assets/ecb91f12-545b-4375-99c0-07c26bb6421a)

## Subtraction  of 8 bit ALP:
```
mov AL,74H
mov BL,69H
SUB AL,BL
HLT
```
## Output :
![sub_8bit](https://github.com/user-attachments/assets/a3e7048a-4896-4e72-bb55-5f76351e71c8)

## Multiplication ALP :
```
org 100h
mov AL,75H
mov BL,32H
MUL BL 
HLT
ret
```
## Output:
![mul_8bit](https://github.com/user-attachments/assets/8201a6f2-e1c9-4593-a5a9-e295833d1746)

## Division ALP :
```
org 100h
mov AL,68H
mov BL,18H
DIV BL
HLT
ret
```
## Output :
![div_8bit](https://github.com/user-attachments/assets/b8287201-d82f-45f1-b98f-880bc9134254)

## Programs for logical operations:
## AND ALP:
```
mov AL,33H
mov BL,44H
AND AL,BL
HLT
```
## OUTPUT :
![logic_AND asm](https://github.com/user-attachments/assets/babed937-bcfd-45d0-b045-7635d539ae27)

## OR ALP :
```
mov AL,33H
mov BL,44H
OR AL,BL
HLT
```
## OUTPUT:
![logic_OR asm](https://github.com/user-attachments/assets/c0cca8d6-3e53-4798-b44c-44f2c480c9ec)

## NOT ALP:
```
mov AL,65H
NOT AL
HLT
```
## OUTPUT:
![logic_NOT asm](https://github.com/user-attachments/assets/f41eba4e-c3f2-48c7-a486-5aa3de4d14bd)

## XOR ALP:
```
mov AL,66H
mov BL,77H
XOR AL,BL
HLT
```
## OUTPUT:
![logic_XOR asm](https://github.com/user-attachments/assets/0c9c3a8c-5593-4b37-8203-3f69939196b8)


## Result :
 The execution of ALP on fundamental arithmetic and logical operations is successfully completed.
