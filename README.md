# esp-32-project

# What is my project ? 

My project is a live, wifi required, survilance camera using Arduino software.
 
 # Why did you choose this project ?
 
 I chose this camera because it falls under my interest in cybersecurity. I use to facetime myself on my mac from my phone to watch my dogs, and make sure they were safe. But with the esp32 watching my loved ones can be so much easier.      
 
 
 # What was the experience installing the ESP32?
 
 Pretty straight forward. May look complex to the naked eye, I had assistance from my professor when I was stuck. If you are feeling stuck, make sure ti retrace your steps for any errors. Ask for help if needed. Small errors can lead to everything failing. 

# What is the future of the ESP32? 

 The future of the ESP32 doesnt have to have limits, the functions go beyond survilance. The goal is to create various functions that allow the ESP 32 to be used for protection purposes. To prevent dangerous situations and be aware of surrounding even when you are not physically there. 
 
 # Software Managing 

Step one : Download software audino  : https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json 
 Failed to download the correct python. 
 
 
 Make sure to download the appropriate version according to your device. 
 
 
 
 Step Two : Select file preferences on the top left corner of Audino and enter the link in step one into "Addiotional Boards Manager"
 
 Step three : Next, select tools "Board: Audino Uno , Boards Manger". Search ESP32 and install it. This will activate the esp32 camera
, in which you will further use it for secuirty reasons by live wifi. 

 Step Four : Select Device Manager to find PORT user, depending on the device, this step may look different for everyone.
 
 Step Five : Select the port you used connected to your device
 
 
 Step Six : Next, Select ESP 32 on "File" , drop down " Examples", then "Camera Web Server" , click and open it.
 
 Step Seven, Scroll down until you locate CAMERA_MODEL_AL_THINKER, delect this line by deleting "//" if needed.
 
 Step Eight : Under " Enter Your Wifi Credentials", choose your desired password, then enter the SSID (wifi) you are using carefully and precisely.
 <img width="546" alt="Screen Shot 2022-12-11 at 8 03 14 PM" src="https://user-images.githubusercontent.com/113206265/206940592-45cfed77-4c6f-4ce4-ac92-3efd534524d7.png">

 Last Step, reset the esp32 by clicking two times and everything should now be set and processed . To see if it is activated, copy and paste the link provided in the screen and enter it in your browser. 
 
 <img width="490" alt="Screen Shot 2022-12-06 at 5 58 38 PM" src="https://user-images.githubusercontent.com/113206265/206940512-8fc61337-e6f9-48ee-842c-e8b71d8e2ff6.png">

 
