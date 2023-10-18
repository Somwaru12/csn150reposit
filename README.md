# CSN 150 Project
## Callmebot and how to send messages on WhatsApp
### Purpose
How to send messages to yourself on Whatsapp using the esp32
#### Equipment
.ESP32
.phone number
.whatsapp
##### Documentation
(https://randomnerdtutorials.com/esp32-send-messages-whatsapp/)
###### Steps 
. I got the whats app set by texting callmebot "I allow callmebot to send me messages"
. This then gave me an API key for my phone number
. I then got the code from the website listed above 
. I applied the changes that were needed to the ssid,wifipass,apikey, and my phone number to the script 
. I uploaded it and reset the ESP once it was uploaded successfully 
. it was successful and I received a message on WhatsApp
####### Problems 
One issue I encountered was the ESP was never connecting. I figured out how to fix this issue by messing with the internet credential and it was wrong. After I fixed this the ESP would connect successfully and          
