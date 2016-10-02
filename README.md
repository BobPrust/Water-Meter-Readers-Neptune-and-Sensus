# Neptune-E-Coder
 Arduino Water Meter Reader and Ethernet Server.
Every hour the Arduino queries the E-Coder water meter for usage and writes the result to an SD card.
On query the Ethernet Server sends data.
The request for data can be; 
1. last 24 hours, 
2. All data last 7 days, 
3. All data last 31 days, 
4. Once a day all data.
5. All data
