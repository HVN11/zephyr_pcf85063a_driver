#
# Copyright (c) 2022 Circuit Dojo LLC
#
# SPDX-License-Identifier: Apache-2.0
#

zephyr_library_amend()
zephyr_library_sources_ifdef(CONFIG_PCF85063A pcf85063a.c)