# ST7789V Fast

The standard ESPHome ST7789V spends *a lot* of time clearing the screen (at least when the screen is large enough that it's display buffer ends up in PSRAM). This component reduces that time by about an order of magnitude. It does however mean that the auto-clear option is no longer respected.