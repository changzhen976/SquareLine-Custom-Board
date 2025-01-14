idf_component_register(SRCS "lvglSpiCfg.c"
                    INCLUDE_DIRS "." 
                    REQUIRES driver lvgl esp_timer esp_lcd indev_port)
