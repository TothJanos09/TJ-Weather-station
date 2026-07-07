Journal for TJ Weather station

Got the idea around 2026 February that I want to measure the weather, that was about the time I started doing little arduino projects like the DHT-11 + LCD. It was good but I knew this was far from what I can achive, I looked online and used AI (Claude) to help me with what I need for this, I found the AHT20+BMP280, VEML7700 I^2C sensors, I knew that I needed to use ESP32 to do this because the arduino lacks connectivity, I ordered the Seeed Studio XIAO C6. 

I also wanted it to be independent, so no external power so I looked into solar panels and batteries, I found that monocrystalline solar panels have the best efficiency and that LiFePO4 batteries have the best specs. Also when using solar panels I need to use Maximum Power Point Tracking devices that actively monitor the solar panel and change the load accordingly so that the solar panel is always at max efficiency. Also for the batteries I have to use a battery managemnt device that prevents shorts and other charging/discharging errors.

Also in the time I got the idea to measure UV, and I wanted to measure it in independently (UV-A, UV-B, UV-C) and thats when dound that the AS7331 is the perfect choice, also I want to measure if its raining or not so I got the XKC-Y25-V  capacitive rain sensor, its a binary on/off digital signal so I had to use the PCF8574 I^2C GPIO expander to attach it to my bus.


The buy phase was around 2026 March-April, also thats when I had lots of test so I couldnt to a lot of meaningful work around that time, but now its summer so im gonna make this work by around august-september (I hope so)

ˇˇˇ How its looking rn  ˇˇˇ

<img width="3216" height="1365" alt="20260707_163433(2)" src="https://github.com/user-attachments/assets/79e91eed-6906-4a93-a09f-4b55170ac465" />
