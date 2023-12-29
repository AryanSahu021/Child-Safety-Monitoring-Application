# Child Safety Monitoring - Android/iOS Application
Designed and deployed an Android/iOS app for a smart bicycle to help parents monitor their child’s safety.

The smart bicycle has embedded hardware sensors and systems such as a gyroscope, accelerometer, GPS, microphone, and antenna. For this problem statement, assume that your Android/iOS mobile phone (Phone A)  behaves as the smart IoT embedded system and you are riding a (sensorless old-fashioned) bicycle. It is able to transmit the data to your partner's device (parents’ Android/iOS mobile hereafter referred to as Phone 😎 for warning.

# The child-monitoring Android/iOS app (during cycling) is able to do the following:

1. Continuously monitor the GPS, accelerometer, and gyroscope data of your phone to determine the following

- Over speed
- Fall detection
- Boundary crossing (defined some geographical coordinates)

2. If the cycle goes beyond a particular perimeter, or over speeds, your device should do the following:
Play a beep alarm sound on your device (Phone A).
Display the real-time location of phone A on phone B using Google Maps and play a beep sound on Phone B.
3. If the cycle falls, your device should do the following:
Play a beep alarm sound on your device (Phone A), with an option to switch OFF the alarm.
Display the real-time location of phone A on phone B using Google Maps and play a beep sound on Phone B.
If the alarm is not switched OFF within 5 seconds by Phone A, a) Switch on the microphone and camera of phone A automatically and start recording. b) Send an SOS from phone A to phone B by transmitting the recorded sound and images using mobile internet network. 

This has been done using the MATLAB Simulink support package for android/ios applications.
