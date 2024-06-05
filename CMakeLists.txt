# Copyright (c) 2024 Sorcerer Corporation

if(CONFIG_COBS_C)
  zephyr_library()

  zephyr_library_sources(cobs.c)

  zephyr_include_directories(.)
endif()