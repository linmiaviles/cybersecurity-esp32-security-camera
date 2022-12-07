# esp-32-project

# What is my project ? 

My project is a live, wifi required, survilance camera using Arduino software.
 
 # Why did you choose this project ?
 
 I chose this camera because it falls under my interest in cybersecurity. 



 # Software Managing 

Step one : Download software audino  : https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json 
 Failed to download the correct python. 
 
 
 Make sure to download the appropriate version according to your device. 
 
 
 
 Step Two : Select file preferences on the top left corner of Audino and enter the link in step one into "Addiotional Boards Manager"
 
 Step three : Next, select tools "Board: Audino Uno , Boards Manger". Search ESP32 and install it. This will activate the esp32 camera
, in which you will further use it for secuirty reasons by live wifi. 

 Step Four : Select Device Manager to find PORT user, depending on the device, this step may look different for everyone.
 
 Step Five : Select the port you used connected to your device.
 
 Step Six : Next, Select ESP 32 on "File" , drop down " Examples", then "Camera Web Server" , click and open it.
 
 Step Seven, Scroll down until you locate CAMERA_MODEL_AL_THINKER, delect this line by deleting "//" if needed.
 
 Step Eight : Under " Enter Your Wifi Credentials", choose your desired password, then enter the SSID (wifi) you are using carefully and precisely.
 
 Last Step, reset the esp32 by clicking two times and everything should now be set and processed . To see if it is activated, copy and paste the link provided in the screen and enter it in your browser. 
