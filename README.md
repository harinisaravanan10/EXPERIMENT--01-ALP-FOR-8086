Name :HARINI.S
Roll no :212223040058
Date of experiment :16.08.2024





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
org 100h
MOV al,11h;
MOV bl,20h;
ADD al,bl;
MOV [6379h],al;
ret

```


## Output  
![Screenshot 2024-08-19 134629](https://github.com/user-attachments/assets/12ee7047-8ad8-421a-b899-628b15993c61)

 
## Subtraction   of 8 bit numbers  ALP 
```
org 100h
MOV al,31h;
MOV bl,20h;
SUB al,bl;
MOV [6379h],al;
ret
```
 
## Output  

![Screenshot 2024-08-19 135509](https://github.com/user-attachments/assets/05267960-10ff-450a-b97a-a13df47ce5ed)

## Multiplication alp 
```
org 100h
MOV al,31h;
MOV bl,2h;
MUL bl;
MOV [6379h],Bl;
ret
```
 ## Output  
![Screenshot 2024-08-19 140313](https://github.com/user-attachments/assets/479e3bb2-4dcb-4e21-86a4-d222c85a3239)


## Division alp 
```
org 100h
MOV al,26h;
MOV bl,[2369h];
DIV bl;
MOV [2399h],al;
ret
```
## Output  

![Screenshot 2024-08-19 141130](https://github.com/user-attachments/assets/2cb2c9a3-bb58-473c-ac2a-3f4c033dc48d)

OR OPERATION

```
org 100h
org 100H
MOV SI,0532H;
MOV AX,0A32H;
MOV BX,0B13H;
OR AX,BX;
ret
```
![Screenshot 2024-08-19 144326](https://github.com/user-attachments/assets/fc72dd0f-b878-43b0-a6d0-b48c7625dc63)

AND OPERATION 

```
org 100H
MOV [SI],AX;
MOV AX,0A32H;
MOV BX,0B13H;
AND AX,BX;
ret
```

![Screenshot 2024-08-19 144640](https://github.com/user-attachments/assets/50d41840-490f-4927-bbec-3ff94acc2319)

XOR OPERATION 

```
org 100H
MOV [SI+2],AX;
MOV AX,0A32H;
MOV BX,0B13H;
XOR AX,BX;
ret
```

![image](https://github.com/user-attachments/assets/4ee7ff4e-8d6b-49c8-9aab-087c222baa7b)

NOT OPERATION

```
org 100H
MOV [SI+4],AX;
MOV AX,0A32H;
NOT AX;
MOV [SI+6],AX;
ret
```

![Screenshot 2024-08-19 190209](https://github.com/user-attachments/assets/669a8737-8daf-4614-a5a3-ae0612c9b690)



## Result :

Thus, ALP for fundamental arithmetic and logical operations are executed successfully.
 








