# Smart B-cane
In order to provide the blind people hearable environment, this project focuses on the field of assistive devices for visual impairment people. It converts the visual
data by image processing into an alternate auditory modality that will be provide the blind user with a robotic vision through speech.
B-cane(Smart Blind Man Stick) contains three main parts, a raspberry pi, a pi camera and an artificial intelligence module. When the user presses the button on the B-cane,
the camera module starts to taking real-time video stream and analyze the
it using Caffe Model to detect the object/person faced by the the user, and then using a speaker or headphone, the device will voice assist the person about the environment.Therefore, the artificial intelligence module is used for modality conversion, from the visual modality to another.


<img src="https://github.com/MadhavShah/Smart-B-cane/blob/master/IMG_20190317_042304.jpeg" rotate="90" />

## Hardware Used:
   * Raspberry Pi 3 B+
   * Pi Camera / Web Cam
   * Ultrasonic Sensors
   * Headphone/speaker and Microphone
   * Motor(partially weight attatched for vibrations)
   
## Software/Library Used:
   * OpenCV
   * MobileNet_V2
   * pyttsx3
   * Twilio Communication API
   
## Functionality:
   * Object/Person Detection using MobileNet_V2.
   * Real time text to speech conversion of object detected.
   * Optical Character Recognition for large street signs.
   * Haptic Feedback using motor via response from ultrasonic sensor.
   * Location logging using location magic.
   * Emergency button is used to send the live location to thier dear ones using Twilio Communication API.
   
Youtube link--  https://youtu.be/L_M9tr_B1Ac
