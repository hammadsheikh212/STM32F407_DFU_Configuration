Custom bootloader and application configuration
DFU_Configuration size is 64kb and starting address is the default one 0800000
DFU_Application size is 960kb and starting address is 0801000
DFU_Configuration will blink Green Led and application code is simply blinking Red Led
first flash application code then dfu_config code.
at start it will first run DFU_Code then after 1 second it will jump to the application code
