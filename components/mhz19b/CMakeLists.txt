set(COMPONENT_SRCDIRS .)
set(COMPONENT_ADD_INCLUDEDIRS .)

set(COMPONENT_REQUIRES log esp_idf_lib_helpers esp_driver_uart esp_driver_gpio)

set(COMPONENT_PRIV_REQUIRES esp_timer)

register_component()
