# BME280-STM32-Driver

## Usage:
    // declare
    #include "BME280.h"
    BME280 bme;
    
    // init
    BME280_Init(&bme, &hspi1, SPI1_CSB_GPIO_Port, SPI1_CSB_Pin);
    
    // main loop
    BME280_updateValues(&bme);
