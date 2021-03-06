# **AUTOMATIC FAN SPEED CONTROL**

## **ABSTRACT**
Now-a-day’s technology is running with time, it completely occupied the life style of human beings. Even though there is such an importance for technology in our routine life there are even people whose life styles are very far to this well known term technology. So it is our responsibility to design few reliable systems which can be even efficiently used by them. Automatic Room Temperature Controlled Fan Speed Controller is one of them. The developed system provides an environment in which no user needed to control the fan speed. Automatically control the fan speed by sensing the room temperature. These fascinating efforts to create intelligent system are to provide human being a more convenient life. The circuit was designed using electronic components available in local market to keep the cost at low level.


## **DESCRIPTION**
This project is a standalone automatic fan speed controller that controls the speed of an electric fan according to our requirement. Use of embedded technology makes this closed loop feedback control system efficient and reliable. Microcontroller (ATMega328) allows dynamic and faster control. Microcontroller is the heart of the circuit as it controls all the functions.
The temperature sensor LM35 senses the temperature and converts it into an electrical signal, which is applied to the microcontroller. The sensed temperature values are simultaneously displayed on the LCD panel. The microcontroller drives motor driver to control the fan speed. This project uses regulated 12V, 2A power supply. This project is useful in process industries for maintenance and controlling of Boilers temperature.

## **REQUIREMENTS**

- **HIGH LEVEL REQUIREMENTS**

  |HLR_ID|High level Description|
  ---|---|
  |HLR01|It shall have a Sensor|
  |HLR02|It shall have a Microcontroller|
  |HLR03|It shall have a Fan|
  |HLR04|It shall have a Display|

- **LOW LEVEL REQUIREMENTS**

  |LLR_ID|Low level Description|
  ---|---|
  |HLR01_LLR01|It shall have a Temperature sensor(LM35) to measure the temperature of the room|
  |HLR02_LLR02|It shall have a Microcontroller(ATmega328) to recieve/transmit the data|
  |HLR03_LLR03|It shall have a Motor Driver to drive the motor|
  |HLR03_LLR04|It shall have a Motor to Spin the fan|
  |HLR04_LLR05|It shall have a LCD Display(16X2) to display the temperture of the room| 



## **ADVANTAGES**
- It is economical and easy to handle.
- Fan runs automatically.
- It is easy to install in heat dissipating devices to cool them down.
- Saves energy by turning off fan automatically at room temperature.



## **APPLICATIONS**
- It can be used to control the temperature of devices, rooms, electronic components, etc.
- It can be used as cooling pads for laptops or computers
- This device is used for cooling the car engine.


## **BLOCK DIAGRAM**

![Block diagram](https://user-images.githubusercontent.com/82401251/156115015-84153921-dd31-4c30-94d8-e386cb172375.jpg)


## **FLOW CHART**

![FLOW CHART (1)](https://user-images.githubusercontent.com/77672209/157167968-8d641a78-fa2c-47aa-a002-8536939590f6.jpg)


## **SYSTEM DESIGN**
![System_Design_New (1)](https://user-images.githubusercontent.com/82401251/156144583-f3b587f2-6b82-4e8c-b74f-8dd5eeca05de.jpg)


## **SUB-SYSTEM DESIGN**

- ###### Temperature Sensor
![Temp_sensor](https://user-images.githubusercontent.com/82401251/155829430-69dfbdf4-8e18-479d-82a5-5890bdd63461.jpg)

- ###### Digital Temperature Sensor
![TC74 Blockdiagram](https://user-images.githubusercontent.com/82401251/156115223-d06eb693-a7f5-4ea3-aeb3-0b63d7616825.jpg)


- ###### Motor Driver
![Motor_Driver](https://user-images.githubusercontent.com/82401251/155829441-028f8f0d-8781-414c-803c-7326ae053076.jpg)

- ###### DC motor
![DC_Motor](https://user-images.githubusercontent.com/82401251/155829443-ef79445e-574d-4c23-baef-0e214194746f.jpg)

- ###### LCD Display
![LCD_Display](https://user-images.githubusercontent.com/82401251/155829447-29c77360-9d51-42b6-aefa-786347ccd581.jpg)




## **COMPONENT DESCRIPTION**

-  ###### Microcontroller
An integrated circuit that contains a microprocessor along with memory and associated circuits and those controls some or all the functions of an electronic device (such as a home appliance) or system.

-  ###### Temperature Sensor
A temperature sensor is a device that is designed to measure the degree of hotness or coolness in an object. The working of a temperature meter depends upon the voltage across the diode.

- ###### Digital Temperature Sensor
The TC74 is a serially accessible, digital temperature sensor particularly suited for low cost and small formfactor applications. Temperature data is converted from the onboard thermal sensing element and made available as an 8-bit digital word.

- ###### DC Motor
A DC motor is an electrical machine that converts electrical energy into mechanical energy. In a DC motor, the input electrical energy is the direct current which is transformed into the mechanical rotation.

- ###### Motor Driver
The motor driver IC is an integrated circuit chip used as a motor controlling device in autonomous robots and embedded circuits. A motor driver is undoubtedly something that makes the motor move as per the given instructions or the inputs (high and low).

- ###### LCD
LCD (Liquid Crystal Display) is a type of flat panel display which uses liquid crystals in its primary form of operation. LEDs have a large and varying set of use cases for consumers and businesses, as they can be commonly found in smartphones, televisions, computer monitors and instrument panels.



## **SIMULIDE OUTPUT**

![Test0](https://user-images.githubusercontent.com/82401251/156877031-255c0583-5f44-4568-a090-3aebfc63e6f8.png)

![test1](https://user-images.githubusercontent.com/82401251/156877048-652b34f2-51d3-4ad6-9b44-9d49419323d9.jpeg)

![Test-2](https://user-images.githubusercontent.com/82401251/156877050-71f12152-07c1-4854-8975-60d75083d6a1.jpeg)

![Test-3](https://user-images.githubusercontent.com/82401251/156877051-ba56f083-f456-4c5e-a076-731c560c08b3.jpeg)
