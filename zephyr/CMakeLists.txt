# Haz que Zephyr vea el raíz del repo (un nivel arriba) como fuente de boards/shields
set(ZMK_CONFIG_ROOT ${CMAKE_CURRENT_LIST_DIR}/..)
list(APPEND BOARD_ROOT  ${ZMK_CONFIG_ROOT})
list(APPEND SHIELD_ROOT ${ZMK_CONFIG_ROOT})
