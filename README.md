# FFBDumyLoad
stm32f103 blue pill based device to log PID FFB effects stream

<img width="1280" height="575" alt="image" src="https://github.com/user-attachments/assets/0f3e6581-3887-4939-8ee2-6351a15670d8" />


Those simple USB device register as usb ffb joystick and CDC virtual com port. When any PID FFB packet is recived, json like log entry is writen to CDC.

Only blue pill board can be used, no need to connect motors and potentiometers.

No drivers or special software needed. Use any serial terminal, like putty.

time is in ms

<img width="2244" height="1187" alt="image" src="https://github.com/user-attachments/assets/ff01d74d-db26-4758-9605-b54e8d12b8c6" />




***

this device can be used as simple ffb stick. it have 4 axis, 16 buttons(4*4 matrix)

!remove EN jumpers from l298 module!

!always use USB isolator if power supply and motors are powered!

uc pins used
<img width="982" height="781" alt="image" src="https://github.com/user-attachments/assets/5fa0dc7a-358f-46dd-8c64-40f02c267481" />

<img width="2082" height="1024" alt="Untitled" src="https://github.com/user-attachments/assets/8c3d2d20-c47e-4a15-9708-5deefc90f5ea" />
