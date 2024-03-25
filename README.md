FreeRTOS task notification API allows inter-task communication and synchronization in real-time embedded systems. 
Using task notification API, tasks can efficiently notify each other of events or synchronize their execution using lightweight notifications. 

This project is a basic implementation of task notification functionality in FreeRTOS

The task is to create 3 tasks that toggle 3 different LEDs and a button task that polls the button press periodically.
If the button task detects a button press, it should send a notification to LED toggling task. When the LED toggling task receives the notification, it should delete itself.
