## Hardware:

#### Screen model:

| SKU | Drivers | Resolution |
| ------------- | ------------- | ------------- |
| MAR2407 | ILI9341/ST7789   | 320x240 |

https://electro-e-shop.com/index.php/product/lcd-tft-2-4-inch-touch-display-for-arduino-uno-mega2560-2/

#### Board:
esp32 with esp-idf framework v5.4

## Software:

#### Dependencies:
lvgl,
esp_lcd_ili9341

#### PRIV_REQUIRES:
esp_driver_gpio,
esp_driver_spi,
esp_driver_ledc,
esp_lcd

#### Connections:
| EXAMPLE_PIN_NUM_SCLK | 18
| EXAMPLE_PIN_NUM_MOSI | 23
| EXAMPLE_PIN_NUM_MISO | 19
| EXAMPLE_PIN_NUM_LCD_DC | 21
| EXAMPLE_PIN_NUM_LCD_RST | 22
| EXAMPLE_PIN_NUM_LCD_CS | 5
| EXAMPLE_PIN_NUM_BK_LIGHT | 2
| EXAMPLE_PIN_NUM_TOUCH_CS | 15
