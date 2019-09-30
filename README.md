# RFID_Excel
Attendance using Arduino and wifi on Excel

This can be used to ensure all employees in the company come in time every day and saved the Excel file where the names and each unique number stored when all employees had come.

![alt text](https://hackster.imgix.net/uploads/attachments/882078/interfacing-of-rfid-rc522-with-arduino_UPp8SPfUtU.jpg?auto=compress%2Cformat&w=1280&h=960&fit=max)

## CONNECTIONS:

![alt text](https://hackster.imgix.net/uploads/attachments/882080/interfacing-of-rfid-rc522-with-arduino_jw3kqpgfGz.png?auto=compress%2Cformat&w=1280&h=960&fit=max)

Connections are made as per the given diagram.

Now open **_Arduino IDE_**, include library files

*#include <SPI.h>*

*#include <MFRC522.h>*

*#include <TimeLib.h>*

After that open **--> Example --> MFRC522 --> RFID** read personal data

After running the code above open serial monitor and show the rfid tag to the reader, thus it will provide the ID of each tags.

![alt text](https://hackster.imgix.net/uploads/attachments/882087/screenshot_(1)_tVeO156tPO.png?auto=compress%2Cformat&w=1280&h=960&fit=max)

In the attachments I have uploaded the source code, add the **CARD ID** to it.

Run the code, open serial monitor

the card ID will be detected, then close serial monitor

Go to **PLX-DAQ** (data acquisition for excel), connect the **COMB** port, now show the **RFID** tag to it, the employees details will be printed.

![alt text](https://hackster.imgix.net/uploads/attachments/882091/screenshot_(2)_zmBs3ZIDt2.png?auto=compress%2Cformat&w=1280&h=960&fit=max)
