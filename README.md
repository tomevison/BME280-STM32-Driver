# BME280-STM32-Driver

## Usage:
    // declare
    #include "BME280.h"
    BME280 bme;
    
    // init
    BME280_Init(&bme, &hspi1, SPI1_CSB_GPIO_Port, SPI1_CSB_Pin);
    
    while(1){
        BME280_updateValues(&bme);
    }
