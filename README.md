 In this example, only one smartphone is used. 2nd LoRa module programmed as a standalone and reply with same message (so 2nd smartphone is not required). The 2nd board is connected to PC and is monitored via Arduino IDE. The input from the smartphone is read by the LoRa board connected to smartphone, and message is sent to the standalone module. Serial communication terminal android application is used here, but new application will be developed using Android Studio. The final product will allow 2 or more smartphones to communicate.

To test the project, user needs 2 Adafruit M0 Feather LoRa RFM95x boards, usb cables (micro-USB to USB-A, and micro-USB to your Android smartphone),

1.	Connect the 1st board to PC via USB.
2.	Open Arduino IDE and open the client file.
3.	Extract RadioHead library zip folder, and add it to Documents/Arduino/libraries folder.
4.	Compile and upload the code.
5.	Disconnect the board from PC and connect it the smartphone.
6.	Install serial USB terminal application in your smartphone from play store (you need to have android developer settings on, and USB debugging on), and turn on the connection with 9600 baud rate setting.
7.	Connect the second board to PC via USB.
8.	Open the server file in Arduino IDE, compile and upload it to the second board.
9.	You can now send messages from smartphone to the board.
