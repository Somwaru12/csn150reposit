# Callmebot and how to send messages on WhatsApp

## Purpose

How to send messages to yourself on Whatsapp using the esp32

### Equipment

1. ESP32
2. Phone number
3. Whatsapp

#### Documentation

(https://randomnerdtutorials.com/esp32-send-messages-whatsapp/)

##### Steps 

1. I got WhatsApp set up by texting callmebot "I allow callmebot to send me messages"
2. This then gave me an API key for my phone number
3. I then got the code from the website listed above 
4. I applied the changes that were needed to the ssid,wifipass,apikey, and my phone number to the script 
5. I uploaded it and reset the ESP once it was uploaded successfully 
6. It was successful and I received a message on WhatsApp

###### Problems 

One issue I encountered was the ESP was never connecting. I figured out how to fix this issue by messing with the internet credential and it was wrong. After I fixed this the ESP would connect successfully and          
