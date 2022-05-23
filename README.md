- 👋 Hi, I’m @Ockertjvn and is 71 years young. I am on pension and looking at my dreams.
- 👀 I’m interested in DIY 3D printers and DIY telescope mounts.  It took me one year and 3 months to build my Delta printer. I have done the printer to 
     show the youngsters that there is nothing wrong with my head or hands.
- 🌱 I’m currently learning how to program a smart phone to be used as a remote to control the telescope. I am using MIT APP inventor.
- I use a Arduino ESP32 Dev Kit connected to a Nokia 5110 LCD as a radio to process all the commands receiving from the Smart phone. I used my WiFi setup at 
     home as a medium to convye all the signals.
- The ESP32 sending the commands (interrupts over 2 pins) via "wire.h" to a Arduino Mega with a RAMPS1.4 shield. There are enough pins:
- It controls my Focus stepper with one limit switch.
- It controls the AZIMUTH stepper with two limits.
- It controls the Altitude stepper with 2 limits.
- it controls the 3D Printer star finder scope focus. The CAM is connected to a Laptop.
- it controls the green laser pointer.
- it controls the mirror heater.
- it controls the setting of micro steps
- four interrupt pins are connected to the AZI and ALT encoders.
- it controls my Raspberry PI camera and sends images to my laptop and other smart phones connected to my WIFI network.
- it sends images to my Raspberry PI that is connected to my TV.
- with the MIT APP I manually point the telescope to objects in the sky.
- All the building blocks are tested and are working.
- The MIT APP sends Date, Time and my GPS to te ESP32
- 
- 💞️ I’m looking to collaborate on the automation of my mount.
- I want a "star database" on the ESP32.  The MIT APP must collect the data from the ESP32, display it and with a button I want to select a star and automation will
   steer the telescope.
- Add a clock to the project.
- understand all the mathematics.
- Use Stellarium as well to see where I am pointing  AND  point a star, click the mouse. Stellarium will send the position to the Arduino and automation will take
   it from there
- 📫 How to reach me ...
Take note. I am very lazy to read e-mail.  I am at annsdadda@gmail.com.
<!---
Ockertjvn/Ockertjvn is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
