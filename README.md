# NX-SerialMonitor

One other use-case for my old Nextion/TJC screens is to turn the device into a Serial Debug Monitor. It will just spit out the serial buffer to the screen, so you can monitor what’s being sent. For example when booting an MCU:

![image](https://user-images.githubusercontent.com/15969459/129595669-4ffef612-2fe3-4f6a-98ad-65af9ee35b10.png)

The UI runs standalone on the Nextion/TJC screen, so no MCU is needed. The code runs on the display. Just hook it up to a serial interface and watch the output scroll by…

![image](https://user-images.githubusercontent.com/15969459/129596329-1c30a531-4925-43a9-909f-0784145cffe2.png)

There is even an onscreen keyboard to send commands over serial too:

![image](https://user-images.githubusercontent.com/15969459/129596707-63f68c13-2eb7-42b0-8559-687c12989471.png)
