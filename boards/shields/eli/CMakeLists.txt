# Este archivo le dice a Zephyr que incluya el soporte de GPIOs externos
if(CONFIG_GPIO_MCP23017)
  zephyr_library_include_directories(${ZEPHYR_BASE}/drivers/gpio)
endif()