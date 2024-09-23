# EXPERIMENT--01-ALP-FOR-8086
Name : JANANI S
Roll no : 212223230086
Date of experiment : 12/08/2024





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
mov AL,53H;
mov BL,24H;
Add AL,BL;
HLT;
```


## Output  
 ![image](https://github.com/user-attachments/assets/3782f42e-df80-4902-be7d-0d2131ed1b68)

## Subtraction   of 8 bit numbers  ALP 
 ```
mov AL,53H;
mov BL,24H;
sub AL,BL;
HLT;
```
## Output  
![image](https://github.com/user-attachments/assets/fcfbd8e2-1143-4cc4-9292-ba3e6a18f6be)

## Multiplication alp 
```
mov AL,53H;
mov BL,24H;
mul AL,BL;
HLT;
```
 ## Output  
![image](https://github.com/user-attachments/assets/b2fc328a-7cbd-4442-9fa6-8c037fcf6ae8)


## Division alp 
```
mov AL,53H;
mov BL,24H;
Div AL,BL;
HLT;
```
## Output  
![image](https://github.com/user-attachments/assets/71b9e5b0-dd31-4d6e-a757-15ec898cbdce)
## Logical AND
```
mov AL,53H;
mov BL,24H;
AND AL,BL;
HLT;
```
## Output
![image](https://github.com/user-attachments/assets/c60a6946-f409-474f-92cc-c2457a868685)
## Logical OR
```
mov AL,53H;
mov BL,24H;
OR AL,BL;
HLT;
```
## Output
![image](https://github.com/user-attachments/assets/9e0eef84-532a-4dc0-b27e-f30eb9498ec5)
## Logical NOT
```
mov AL,53H;
not AL;
HLT;
```
## Output
![image](https://github.com/user-attachments/assets/247c8d7d-00c1-48b0-84c7-5f464a2812f3)
## Logical XOR
```
mov AL,53H;
mov BL,24H;
XOR AL,BL;
HLT;
```
## Output 
![image](https://github.com/user-attachments/assets/3dd60c40-f479-46e1-adfd-1213d84ebbfb)

## Result :
Thus the program for arithmetic operations and logical operations are completed.








