# IoT Weather Indicator
This project is focused on creating an IoT Weather Indicator. By using an API, I seized information about my local weather to then display it on a OLED screen through an ESP 32.

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Audrey L | Mission San Jose High School | Electrical Engineering | Incoming Junior

![Headstone Image](https://bluestampengineering.com/wp-content/uploads/2016/05/improve.jpg)
  
# Final Milestone
My final milestone is the increased reliability and accuracy of my robot. I ameliorated the sagging and fixed the reliability of the finger. As discussed in my second milestone, the arm sags because of weight. I put in a block of wood at the base to hold up the upper arm; this has reverberating positive effects throughout the arm. I also realized that the forearm was getting disconnected from the elbow servo’s horn because of the weight stress on the joint. Now, I make sure to constantly tighten the screws at that joint. 

[![Final Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1612573869/video_to_markdown/images/youtube--F7M7imOVGug-c05b58ac6eb4c4700831b2b3070cd403.jpg )](https://www.youtube.com/watch?v=F7M7imOVGug&feature=emb_logo "Final Milestone"){:target="_blank" rel="noopener"}

# Second Milestone
My second milestone was displaying the temperature of my city on the OLED screen. An OLED screen is a piece of technology that utilizes LEDs, where organic molecules produce light. The model that I am using has four pins and communicates with microcontrollers that use an I2C communication protocol. To continue off of milestone #1, I had to connect the OLED screen to the ESP32. To join the OLED screen to the ESP32, I need to solder in the header pins into the OLED Screen. By using a solder machine, I was able to place these pins into the correct holes permanently. I then connected female to female wires to the correct ports of the OLED screen and ESP32. 
(Inset Image of connection)
|**(OLED display)→(ESP32)**|
|:--:|
|GND → GND|
|VCC → 3V3|
|SCL → D22|
|SDA → D21

![Connection Ports](file:///Users/audreylee/Pictures/Photos%20Library.photoslibrary/resources/derivatives/A/AAA62041-0131-4E8D-A0A9-EE0ACCE58781_1_105_c.jpeg)

Now that all the correct pins are connected, I needed to install the required libraries. I then downloaded Adafruit SSD1306 and Adafruit GFX, which will control the OLED display through the ESP32. However, Adafruit SSD1306 was not the correct library needed, so instead, I downloaded a different library, the Adafruit SH110X. This library allowed me to display both words and images onto the OLED screen. I then began to add to my code from my last milestone. I made sure to include the libraries that will be used throughout this code in the very beginning. The line of code that says the library's name before the function display is used to call which dimensions of this display that I would be using. In this case, I want to have the ability to use the entire screen. So by having the dimensions of (128, 64), this grants me that access. Below the deserialization code, you can see code that is meant to print out the temperature onto the display. 

<img width="255" alt="Screen Shot 2021-07-16 at 12 19 32 PM" src="https://user-images.githubusercontent.com/43714174/125998343-e63b9027-1e11-43c0-9199-2f8c8c013520.png">

The first line of this section is dedicated to printing the temperature data to the serial port. The following two lines are there to set the color and size of what will be displayed. The following line then sets the location of where the data will be printed. Finally, the display function then calls for the temperature to be displayed on the screen. Compared to the last milestone, this milestone I encountered more difficult challenges. First up is that my OLED display was not functioning correctly and appeared to be broken. Another challenge was that I could not find a working library for this specific display. The final libraries that I ended up using were the Adafruit SH110X and Adafruit GFX.

[![Third Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1612574014/video_to_markdown/images/youtube--y3VAmNlER5Y-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=y3VAmNlER5Y&feature=emb_logo "Second Milestone"){:target="_blank" rel="noopener"}
# First Milestone
  

My first milestone was creating a functioning code that enabled my ESP32 to connect to Wi-Fi. An ESP32 is a powerful Wi-Fi/Bluetooth-enabled SoC with a massive GPIO count. By granting this access, the ESP32 was capable of using APIs, specifically ones that contained information about my local weather, which then allows me to now manage this data and use it however I see fit for this project. Beginning this first milestone was making sure my laptop had all the necessary software and applications, such as Arduino and CP210x VCP Driver. Arduino's software is where all my written code throughout this project will be placed for my ESP32 to run. The CP210x VCP Driver is what allows me to download the Arduino IDE and have my code upload to the ESP32. The first piece of code I created was dedicated to connecting my ESP32 to the Arduino application [Tutorial #1](https://www.youtube.com/watch?v=wNtGHCrO7E4). After doing so, I then wrote another code to program my ESP32 to connect to my house's Wi-Fi [Tutorial #2](https://techtutorialsx.com/2017/04/24/esp32-connecting-to-a-wifi-network/). Using a website called [Open Weather](https://openweathermap.org/), I created an API password and used an API call that required my zip code and city name. This API allows me to use my local weather information in my code. I then added onto my previous code that involved connecting my ESP32 to Wi-Fi. This code used a GET request to use this API and display the information I want about the weather [Tutorial #3](https://www.youtube.com/watch?v=s_2cw0k6lgs&t=11s). Now that I have the necessary code, my job is to deserialize it to only display the information I want and in the suitable unit [Tutorial #4](https://arduinojson.org/v6/doc/deserialization/). At last, my code now displays the weather accurately in Fahrenheit. A challenge I faced is writing unfimilar code, and to overcome this challenge I did enough research to better understand how to write suitable code for this script.  


[![First Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1612574117/video_to_markdown/images/youtube--CaCazFBhYKs-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=CaCazFBhYKs "First Milestone"){:target="_blank" rel="noopener"}
