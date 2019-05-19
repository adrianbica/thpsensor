# thpsensor
Bluetooth custom profile on nRF52840-DK board

This is a custom profile with three services:
1. THP Sensing Service has three characteristics:
    a. Humidity characteristic
    b. Pressure characteristic
    c. Temperature characteristic
    
    The service is built around a BME280 sensor connected on the I2C bus to nRF52840-DK board
    
2. LED Service has one characteristic:
    a. Digital characteristic 
    
    This service is used to control the four LED's on the DK board
    
3. Relay Service has one characteristic:
    a. Digital characteristic
    
    This service is used to control four relays connected to the GPIO's on the DK board