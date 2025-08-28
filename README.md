# AVR-Xminis

This is an Arduino core for the Microchip boards

- ATmega328P Xplained Mini,
- ATmega168BP Xplained Mini, and
- ATmega328PB Xplained Mini.

These boards contain an embedded debugger and programmer, and their footprint is compatible with the Arduino Uno R3 board. Since a platform-agnostic debugging solution exists for the Arduino IDE 2, which is compatible with the embedded debugger on these boards, they are ideal for developing Arduino applications. 

After installing this core, you can program and upload Arduino sketches immediately. Furthermore, no preparations are necessary to begin debugging. Well, one should activate the "Optimize for Debugging" entry in the `Sketch` menu. One can upload the code to the board and then press the debug button. Actually, it is not strictly necessary to upload the code before starting debugging, because it will be loaded at the beginning of the debugging session. However, uploading before debugging is usually faster. 