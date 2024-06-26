Name:Nagireddy Avinash Reddy
Company:CODTECH IT SOLUTIONS 
ID:CT06ES315
Domain:Embedded Systems
Duration:15 June to 30jul 2024
Mentor:G .Sravani
Overview of the project: ![Screenshot 2024-06-25 201325](https://github.com/Avinash832860/task2/assets/173812712/b581913a-0e6f-4c01-bde8-6c336d59ff7c)
Experiment: Temperature and Humidity Monitoring with DHT Sensor 
Objective: It measures the surrounding air and gives a calibrated digital signal output of temperature and relative humidity.
Apparatus: *Evaluation Kit *Digital Humidity Sensor EEH110 & EEH210 *8 bit Microcontroller Procedure *First we need to included the DHT library which can be found from the Arduino official website. *Then define the pin number to which our sensor is connected and create a DHT object. *In the setup section we need to initiate the serial communication because we will use the serial monitor to print the results. *Using the read22() function we will read the data from the sensor and put the values of the temperature and the humidity into the t and h variables. *If you use the DHT11 sensor you will need to you the read11() function. *At the end we will print the temperature and the humidity values on the serial monitor.
Precautions: *Avoid using the sensors outdoor, in locations exposed to direct sunlight, or in locations where the temperature may vary rapidly and repeatedly. *Otherwise, the internal parts and the case may deteriorate. *Avoid using the sensors in locations where chemical, organic solvents or other such materials may splatter. Result: After executing the programming the it displays the reading on an LCD screen or on a serial monitor.# task2
