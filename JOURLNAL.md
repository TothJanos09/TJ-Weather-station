Journal for TJ Weather station

Got the idea around 2026 February that I want to measure the weather, that was about the time I started doing little arduino projects like the DHT-11 + LCD. It was good but I knew this was far from what I can achive, I looked online and used AI (Claude) to help me with what I need for this, I found the AHT20+BMP280, VEML7700 I^2C sensors, I knew that I needed to use ESP32 to do this because the arduino lacks connectivity, I ordered the Seeed Studio XIAO C6. 

I also wanted it to be independent, so no external power so I looked into solar panels and batteries, I found that monocrystalline solar panels have the best efficiency and that LiFePO4 batteries have the best specs. Also when using solar panels I need to use Maximum Power Point Tracking devices that actively monitor the solar panel and change the load accordingly so that the solar panel is always at max efficiency.

Also in the time I got the idea to measure UV, and I wanted to measure it in independently (UV-A, UV-B, UV-C) and thats when the 
