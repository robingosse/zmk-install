# SPDX-License-Identifier: MIT

zephyr_library()
zephyr_library_sources_ifdef(
  CONFIG_SHIELD_GOSSIEKEYDACTYLMANUALPHA001_LEFT
  gossiekeydactylmanualpha001.dtsi
)

zephyr_library_sources_ifdef(
  CONFIG_SHIELD_GOSSIEKEYDACTYLMANUALPHA001_RIGHT
  gossiekeydactylmanualpha001.dtsi
)
