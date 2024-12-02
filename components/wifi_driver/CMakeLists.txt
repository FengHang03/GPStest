idf_component_register(SRCS "wifi_driver.c"
    INCLUDE_DIRS "."
    REQUIRES nvs_flash lwip esp_wifi)  