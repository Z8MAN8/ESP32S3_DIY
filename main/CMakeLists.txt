idf_component_register(SRCS "msc_example_main.c"
                    INCLUDE_DIRS "" "$ENV{IDF_PATH}/examples/peripherals/i2s/common"
                    PRIV_REQUIRES usb fatfs esp_driver_gpio esp_timer esp_driver_i2s
                    )
