# Security-Access-using-RFID

This project aims in designing a completely automated security access system for domestic and industrial applications.
Here we aim for security access system for the college campus. 
Security is the bigger concern for an individual or a firm. 
Recognizing the need of security we develop an automated security access system with user friendly access.

# Hardware Configuration

1. Arduino Uno
2. RC522 - RFID Reader/Writer
3. Breadboard
4. Connecting wires
5. Buzzer
6. Servo Motor

# Software Configuration

1. Arduino IDE

# Working of RFID

Systems that make use of RFID technology are typically composed of three key elements:
1. An RFID tag, or transponder, that carries object-identifying data.
2. An RFID tag reader, or transceiver, that reads and writes tag data.
3. A back-end database, that stores records associated with tag contents.

Each tag contains a unique identity code. 
An RFID reader emits a low-level radio frequency magnetic field that energizes the tag. 
The tag responds to the reader’s query and announces its presence via radio waves, transmitting its unique identification data. 
This data is decoded by the reader and passed to the local application system via middleware.
The middleware acts as an interface between the reader and the RFID application system. 
The system will then search and match the identity cgit ode with the information stored in the host database or backend system.
In this way, accessibility or authorization for further processing can be granted or refused, depending on results received by the reader and processed by the database.

# References

1. https://www.youtube.com/watch?v=3uWz7Xmr55c
2. https://goo.gl/wBbnB1
3. https://www.irjet.net/archives/V5/i3/IRJET-V5I3731.pdf
4. https://www.irjet.net/archives/V5/i4/IRJET-V5I484.pdf
5. https://goo.gl/Y6m0Cg