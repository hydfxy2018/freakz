CONTIKI = ../os
ZIGBEE_PATH = ../freakz
ROOT_DIR = ..
FREAKUSB_PATH = ../freakusb

SOURCEDIRS += .

RAVEN_USB_DIR = ./test_avr_ravenusb
PROJECT_OBJECTFILES += ${addprefix $(OBJECTDIR)/,${call oname, $(CONTIKI_SOURCEFILES)}}
CONTIKIDIRS += . $(FREAKUSB_PATH) $(RAVEN_USB_DIR)

include $(RAVEN_USB_DIR)/Makefile
include $(CONTIKI)/Makefile.include