AUTOMAKE_OPTIONS = gnu

SUBDIRS = \
	include input getrc fx2

if BOXTYPE_ARMBOX
if BOXMODEL_VUPLUS_ARM
SUBDIRS += \
	stb-startup-vu \
	stb-backup
else
SUBDIRS += \
	stb-startup \
	stb-backup \
	stb-switch-rc
endif
endif

#if BOXTYPE_ARMBOX
#SUBDIRS += \
#	stb-startup-ddt \
#	stb-backup
#endif
