
###  DATE: 

###  NAME: 
###  ROLL NO :
###  DEPARTMENT: 

# EXPERIMENT--04-INTERFACING IOT DEVELOPMENT BOARD AND CONFIGURE USART FOR TRANSFERRING STRINGS 
## Aim: To Interface iot development board for configuring the the usart and transfer strings though it 
## Components required: STM32 CUBE IDE, ARM IOT development board,  STM programmer tool, Serial port utility tool 
## Theory 
The full form of an ARM is an advanced reduced instruction set computer (RISC) machine, and it is a 32-bit processor architecture expanded by ARM holdings. The applications of an ARM processor include several microcontrollers as well as processors. The architecture of an ARM processor was licensed by many corporations for designing ARM processor-based SoC products and CPUs. This allows the corporations to manufacture their products using ARM architecture. Likewise, all main semiconductor companies will make ARM-based SOCs such as Samsung, Atmel, TI etc.


1.select the appropriate pins as gipo, in or out, USART or required options and configure 
![image](https://user-images.githubusercontent.com/36288975/226189403-f7179f1a-3eae-4637-826b-ab4ec35ba1e1.png)
![image](https://user-images.githubusercontent.com/36288975/226189425-2b2414ce-49b3-4b61-a260-c658cb2e4152.png)
configure in the usart 2 as asynchronous mode and set the baud rate as 115200 as shown below 
![image](https://user-images.githubusercontent.com/36288975/234776631-d6a84ef4-904c-4eac-98ed-ab6253e9379c.png)

  
2.click on cntrl+S , automaticall C program will be generated 
![image](https://user-images.githubusercontent.com/36288975/226189443-8b43451d-0b14-47e4-a20b-cc09c6ad8458.png)
![image](https://user-images.githubusercontent.com/36288975/226189450-85ffa969-2ffb-4788-81e5-72d60fdda0f1.png)
8. edit the program and as per required 
![image](https://user-images.githubusercontent.com/36288975/226189461-a573e62f-a109-4631-a250-a20925758fe0.png)

3. use project and build all 
![image](https://user-images.githubusercontent.com/36288975/226189554-3f7101ac-3f41-48fc-abc7-480bd6218dec.png)
10. once the project is bulild 
![image](https://user-images.githubusercontent.com/36288975/226189577-c61cc1eb-3990-4968-8aa6-aefffc766b70.png)

4. click on debug option 
![image](https://user-images.githubusercontent.com/36288975/226189625-37daa9a3-62e9-42b5-a5ce-2ac63345905b.png)

5 connect the  ARM board to power supply and usb 


6. check for execution of the output using run option
7. Opend serial port utility and check the outpu t



## STM 32 CUBE PROGRAM :



## Output screen shots of Serial port utility   :
 
 
 
 
## Result :
configuring and usart is accomplished and string data is visualized on the serial port utilty
