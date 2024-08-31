# PrecisionAgriculture

- This project presents the design, development, and deployment of a low-power, long-range 
wireless sensor network (WSN) for precision agriculture, utilizing STM32 microcontrollers 
and LoRa technology. The system aims to address the challenges of limited coverage and 
battery life faced by traditional precision agriculture solutions. By leveraging LoRa’s 
capability to transmit data over distances up to 10 kilometers, this project provides a 
scalable and cost-effective solution for monitoring critical environmental parameters, 
including soil moisture, temperature, humidity, and light intensity, in remote agricultural 
fields.
- The sensor nodes, based on the STM32WL55JC1 microcontroller, integrate multiple sensors 
such as the DHT22, BH1750, and HW-390 to collect and transmit data via the LoRaWAN 
protocol. A Dragino gateway forwards the data to The Things Stack network server, where it 
is processed and subsequently visualized on the ThingsBoard platform, enabling real-time 
data-driven decision-making for farmers. The system emphasizes low power consumption, 
with the microcontroller entering stop mode when idle, drawing an average current of 7-12 
mA. Powered by a 4000mAh 7.4V LiPo battery, the sensor nodes achieve a battery life of 
approximately 14 to 24 days, with potential future enhancements including solar or energy 
harvesting technologies for self-sufficiency.
- The implementation demonstrates minimal deviation between sensor readings and actual 
environmental conditions, validating the accuracy and reliability of the system. This 
innovation in precision agriculture empowers farmers to optimize resource management, 
improve crop yields, and promote sustainable farming practices, making it a promising 
solution for the future of agriculture.
