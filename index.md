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
My final milestone is the increased reliability and accuracy of my robot. I ameliorated the sagging and fixed the reliability of the finger. As discussed in my second milestone, the arm sags because of weight. I put in a block of wood at the base to hold up the upper arm; this has reverberating positive effects throughout the arm. I also realized that the forearm was getting disconnected from the elbow servo’s horn because of the weight stress on the joint. Now, I make sure to constantly tighten the screws at that joint.

[![Third Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1612574014/video_to_markdown/images/youtube--y3VAmNlER5Y-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=y3VAmNlER5Y&feature=emb_logo "Second Milestone"){:target="_blank" rel="noopener"}
# First Milestone
  

My first milestone was being able to create functioning code that enabled my ESP 32 to connect to wifi. An ESP 32 is a powerful Wi-Fi/Bluetooth-enabled SoC with a massive GPIO count. By granting this access, the ESP 32 was capable of using API's, specifically ones that contained information about my local weather, which then allows me to now contain this data and use it however I see fit for this project. Beginning this first milestone was making sure my laptop had all the necessary softwares and applications, such as Arduino and CP210x VCP Driver. Arduino's software is where all my written code throughout the etirety of this project will be placed in order for my ESP 32 to run. The CP210x VCP Driver is ... The first piece of code I created was dedicated to connecting my ESP 32 to the Arduino application (https://www.youtube.com/watch?v=wNtGHCrO7E4, Tutorial#1). After doing so I then wrote another piece of code to progrma my ESP 32 to connect to my house's wifi (https://techtutorialsx.com/2017/04/24/esp32-connecting-to-a-wifi-network/, Tutorial#2). By using a website called Open Weather, I created an API password and used an API call which required my zipcode and city name. This API allows me to use my use my local weather's information in my code. I then added onto my previous code that involved connecting my ESP 32 to wifi. This code used a GET request to use this API and display the information I want about the weather (https://www.youtube.com/watch?v=s_2cw0k6lgs&t=11s, Tutorial#3). Now that I have the necessary code, my job now is to deseralize it to only display the information that I want and in the right unit (https://arduinojson.org/v6/doc/deserialization/, Tutorial#4). At last, my code now displays the weather in farenheit. 


[![First Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1612574117/video_to_markdown/images/youtube--CaCazFBhYKs-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=CaCazFBhYKs "First Milestone"){:target="_blank" rel="noopener"}
