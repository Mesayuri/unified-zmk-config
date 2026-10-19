if(CONFIG_SHIELD_SOSHO_R_TRACKBALL OR CONFIG_SHIELD_SOSHO_L_TRACKBALL)
  zephyr_sources(src/boot_delay_hack.c)
endif()
