idf_component_register(
    SRCS src/tmc2209.cpp
    INCLUDE_DIRS include
    REQUIRES esp_driver_gpio esp_timer esp_driver_uart
)
