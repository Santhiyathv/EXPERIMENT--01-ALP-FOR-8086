# EXPERIMENT--01-ALP-FOR-8086
## Name : SANTHIYA B
## Roll no: 212224230247
## Date of experiment : 01.09.2025





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

## Addition  of 8 bit ALP
```
Mov AL,11H
MOV BL,09H
ADD AL,BL
HLT
```



## Output
<img width="1803" height="1024" alt="image" src="https://github.com/user-attachments/assets/d166f4c0-0561-4980-819e-818ddb2a94be" />

 
## Subtraction   of 8 bit numbers  ALP
```
Mov AL,11H
MOV BL,09H
SUB AL,BL
HLT
```
 
## Output
<img width="1641" height="971" alt="image" src="https://github.com/user-attachments/assets/6128166c-38bf-4db1-abe0-12db6c7b877d" />

## Multiplication alp 
```
org 100h
Mov AL,11H
MOV BL,09H
MUL BL
HLT
ret
```
 ## Output 
 <img width="1652" height="896" alt="image" src="https://github.com/user-attachments/assets/675e1aee-c40f-4836-ae3f-ee3432929349" />



## Division alp
```
MOV AL,11H
MOV BL,09H
DIV BL
HLT
```

## Output  
<img width="1417" height="824" alt="image" src="https://github.com/user-attachments/assets/33e60be6-8d7a-49f6-af2c-6c5dca79adba" />

## AND 
```
MOV AL,23H
MOV BL,03H
AND AL,BL
HLT
```

## Output
<img width="1597" height="878" alt="image" src="https://github.com/user-attachments/assets/50f68d6a-a378-4595-85aa-66039b685753" />

## OR
```
MOV AL,23H
MOV BL,03H
OR AL,BL
HLT
```
## Output
<img width="1377" height="821" alt="image" src="https://github.com/user-attachments/assets/727848de-a3f7-4801-8025-1f7f2c729208" />

## NOT
```
MOV AL,21H
NOT AL
HLT
```
## Output
<img width="1399" height="800" alt="image" src="https://github.com/user-attachments/assets/83c764f4-9eb0-4c98-8991-62b5784f6f2d" />

## XOR
```
MOV AL,21H
MOV BL,08H
XOR AL,BL
HLT
```

## Output
<img width="1482" height="791" alt="image" src="https://github.com/user-attachments/assets/47c5b725-bfd3-404b-8662-9ab0a30f9e0b" />

## NAND
```
MOV AL,21H
MOV BL,08H
AND AL,BL
NOT AL
```
## Output
<img width="1300" height="747" alt="image" src="https://github.com/user-attachments/assets/ce2ac1fc-20a2-4d75-9ca8-71093daabef5" />


## Result :
Thus,ALP for fundamental arthimetic and logical operations are executed successfully.

 








