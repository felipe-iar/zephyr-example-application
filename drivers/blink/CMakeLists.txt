# Copyright (c) 2026 IAR Systems AB
# SPDX-License-Identifier: Apache-2.0

zephyr_library()
zephyr_library_sources_ifdef(CONFIG_BLINK_GPIO_LED gpio_led.c)
