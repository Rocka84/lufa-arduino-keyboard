#
#             LUFA Library
#     Copyright (C) Dean Camera, 2010.
#
#  dean [at] fourwalledcubicle [dot] com
#      www.fourwalledcubicle.com
#

# Makefile to build all the LUFA Projects. Call with "make all" to
# rebuild all projects.

# Projects are pre-cleaned before each one is built, to ensure any
# custom LUFA library build options are reflected in the compiled
# code.

all:
	$(MAKE) -C arduino-keyboard clean
	$(MAKE) -C arduino-keyboard all

%:
	$(MAKE) -C arduino-keyboard $@
