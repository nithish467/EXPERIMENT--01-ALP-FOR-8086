# EXPERIMENT 01- ARITHMETIC OPERATION AND LOGICAL OPERATION IN 8086
### Name : NITHISHKUMAR S
### Roll no : 212223240109 





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

mov ax,2A35h   ; first number
mov bx,1F4Bh   ; second number
add ax,bx      ; AX = AX + BX

ret

```



## Output  
<img width="1920" height="1080" alt="Screenshot (6)" src="https://github.com/user-attachments/assets/0f5120d0-fa10-48df-b197-896d8714df7b" />

 
## Subtraction   of 8 bit numbers  ALP 
```
org 100h

mov ax,6a25h
mov bx,2f15h
sub ax,bx    ; AX = AX - BX

ret

```


 
## Output 

<img width="1920" height="1080" alt="Screenshot (7)" src="https://github.com/user-attachments/assets/d77c651c-368c-45c0-ba27-d4278fcae991" />


## Multiplication alp 

```

org 100h

mov ax,1234h
mov bx,0005h
mul bx       ; DX:AX = AX * BX

ret

```
 ## Output  
 <img width="1920" height="1080" alt="Screenshot (8)" src="https://github.com/user-attachments/assets/3c5e8191-4d3d-44ec-a70e-d6125f45b570" />

 


## Division alp 
```
org 100h

mov ax,5000h
mov bx,0010h
div bx       ; AX = quotient, DX = remainder

ret

```

## Output 
<img width="1920" height="1080" alt="Screenshot (9)" src="https://github.com/user-attachments/assets/64e623b8-9a4f-4423-823d-73814ed1bedb" />


AND of 16 bit numbers ALP

```
org 100h

mov ax,2a35h
mov bx,5f35h

and ax,bx

hlt

```

##output
<img width="1118" height="801" alt="Screenshot 2025-08-21 133453" src="https://github.com/user-attachments/assets/bcd11a97-056f-4338-868c-885be59fce96" />


## OR of 16 bit numbers ALP
```
org 100h

mov ax,2a35h
mov bx,5f35h

or ax,bx

hlt
```
## Output 
<img width="1101" height="811" alt="Screenshot 2025-08-21 133600" src="https://github.com/user-attachments/assets/9888f810-39a8-40db-882c-492ffaed76a3" />

## NOT of 16 bit numbers ALP
```
org 100h

mov ax,2a35h

not ax

hlt
```
## Output 
<img width="1089" height="807" alt="Screenshot 2025-08-21 133804" src="https://github.com/user-attachments/assets/45c4e083-ee05-4d6c-b903-8c0cf0240652" />

## XOR of 16 bit numbers ALP
```
org 100h

mov ax,2a35h
mov bx,5f35h

xor ax,bx

hlt
```
## Output
<img width="1113" height="815" alt="Screenshot 2025-08-21 133709" src="https://github.com/user-attachments/assets/e57f1779-b8ac-4760-9ef3-e4139680cf50" />




## Result :
 The execution of ALP on fundamental arithmetic and logical operations is successfully completed.









