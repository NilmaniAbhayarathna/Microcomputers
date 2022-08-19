# Microcomputers - EC2131
Lab-04

## OBJECTIVES
Develop a small water level controlling system of a water tank using the knowledge of interrupts and other programming techniques of PIC16f877a

## INTRODUCTION
The task was to design a circuit and program it with a PIC16F877A.

One of the most well-known microcontrollers in the industry is the PIC microcontroller PIC16f877a. It is quite easy to code or program this microcontroller, and it is also very convenient to use. The fact that it employs FLASH memory technology is one of its key advantages because it allows for unlimited write-erase cycles. There are 33 input and output pins out of a total of 40 pins on it. Numerous applications with pic microcontrollers use the PIC16F877A. PIC16F877A are widely used in digital electrical circuits as well.

<image src = "https://user-images.githubusercontent.com/111268465/185557347-3b599ba4-1a1a-421f-b935-e778d859f728.png" width = 300 height = 200>
  


### TASK
Below is a water tank that has two DC motors where the motor one is used to pump the water into the tank the motor two is used to suck the water out from the water tank and there are three sensors that are used to measure the water level of the tank.

<image src = "https://user-images.githubusercontent.com/111268465/185360443-1f7e43f5-4da9-4d61-a541-792ddff3428b.png" width = "500" height = "250" />

The operations of the two DC motors according to the switch state is given in the following  table. 

<image src = "https://user-images.githubusercontent.com/111268465/185362506-5dec6287-6b1c-4bd1-bbe5-c5014c13f298.png" width = "500" height = "100" />

## APPARATUS
<li>Designed PCB Layout
<li>Pic16F877A - 1
  <li>Breadboard - 1
    <li>DC Batteries(1.5V) - 2
     <li>1k Resistor - 1
  <li>3V DC motors - 2  
    <li>IR obstacle Avoidance Sensors - 3
      <li>40 Pin IC Base - 1
        <li>20Mhz Crystal Oscillator - 1
          <li>220uf Electrolytic Capacitor - 1
            <li>NPN Transistor - 1
              <li>5V Relay - 1
                <li> Jumper Wires 
                  <li>PicKit3
                    <li>MPLAB IDE Software
                
                      
                      
## PROCEDURE
firstly, the PCB layout was designed and printed.
                      
<image src = "https://user-images.githubusercontent.com/111268465/185646779-c21434e8-7ef7-45c2-9125-10dd60581d5a.jpg" width = 300 height = 250>

                      
Next, the pic16F877A was programmed as required using PicKit3 and MPLAB IDE software.
                      
<image src = "https://user-images.githubusercontent.com/111268465/185560137-bc5c0ca4-d3ac-4a09-872d-af1f8b2f615d.jpg" width = 600 height = 300>
<image src = "https://user-images.githubusercontent.com/111268465/185560381-55626a37-f3db-4fcb-8edd-34b9a87d29e4.jpg" width = 600 height = 300>


Finally, the necessary circuit was created by connecting the components and the pic16F877A was connected to the circuit and powered on.

<image src = "https://user-images.githubusercontent.com/111268465/185557954-21cf6e88-18b2-4fa1-8e88-e73a8637276c.jpg" width = 200 height = 300>
  
                        



 
                      
                      
                      
## OBSERVATION
<li>Both motors were not working when all three sensors were off.
                      
<li>When the first sensor was on, only the first motor started working.
                      
<li>When the first and second sensors were on, only the first motor was working.
                      
<li>When all three sensors were on, the first motor stopped working and the second motor started working only for 500ms.
  
 
## DISCUSSION
Working in this laboratory caused certain challenges for us. Human and equipment mistake are the causes of these problems. We printed the wrong side of the PCB and connected it incorrectly the first time we printed it. Sensors and switches are employed in this circuit. In order to use switches and sensors, we had to update the code. In addition, there were a few issues with power delivery. 5V had to be delivered, but it couldn't be provided in a reliable manner. Several approaches were tried until a relay module was able to supply the necessary electricity.
  
## CONCLUSION
This lab was completed as group work, which improved our capacity for teamwork. We encountered a variety of challenges while we created the code and designed the circuit. Especially while we were performing the hardware demonstration, it was a terrific experience to identify mistakes and decide how to fix them as a group. We were able to understand the behavior of the pic16f877a and other components properly. In conclusion, the task was completed satisfactorily, and the result was what was expected.
  




