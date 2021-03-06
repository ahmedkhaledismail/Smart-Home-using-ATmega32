# Smart-Home-System-using-Atmega32-microcontroller
An implementation of smart home system using ATmega32 microcontroller.

The aim of that project is to mimic the implementation of smart home system using ATmega32 microcontroller. This project represents a home consisting of 4 Rooms, a TV, and an Air-Conditioner (AC). Each facility of the home represented by a Light Emitting Diode (LED). There are 3 modes of operation for using that system, i.e., admin mode, guest mode, or block mode. Initially, the first user of the system will set up the login passwords for both the admin and guest users. After successful sign in for guest mode or admin mode, a predefined timer will count down till session timeout occurs. Whenever a user tries to sign in for one of the two modes for 3 wrong trials, the system will be in block mode for 20 seconds. 
This project use two ATmega32 microcontrollers to isolate the independent functions from each other. The two ICs communicate with each other using Serial Peripheral Interface (SPI) protocol. The input is taken from the user using a  4x4 Keypad controlled by the master IC. The user can interact with the interface supplied by the Lucid Crystal Display (LCD) controlled by master IC. The master microcontroller transfers action to the slave microcontroller to take actions based on user input. Environment temperature will be feed to the AC driver using LM35 temperature sensor. 

### Program startup
![image info](https://github.com/ahmedkhaledismail/Smart-Home-using-ATmega32/blob/main/Figures/program%20startup.png)
### Modes of operation
![image info](https://github.com/ahmedkhaledismail/Smart-Home-using-ATmega32/blob/main/Figures/modes%20of%20operation.png) 
### Block mode
![image info](https://github.com/ahmedkhaledismail/Smart-Home-using-ATmega32/blob/main/Figures/block%20mode.png) 
### Home facilities for guest user mode
![image info](https://github.com/ahmedkhaledismail/Smart-Home-using-ATmega32/blob/main/Figures/homes%20facilities%20in%20guest%20mode.png) 
### Extended home facilites for admin user mode
![image info](https://github.com/ahmedkhaledismail/Smart-Home-using-ATmega32/blob/main/Figures/extended%20home%20facilites%20for%20admin%20mode.png) 



