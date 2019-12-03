AUTOMAKE_OPTIONS = gnu

SUBDIRS = \
	include \
	input \
	getrc

if BOXTYPE_ARMBOX
if BOXMODEL_VUDUO4K
SUBDIRS += \
	stb-startup-vu
else
if BOXMODEL_VUSOLO4K
SUBDIRS += \
	stb-startup-vu
else
if BOXMODEL_VUUNO4K
SUBDIRS += \
	stb-startup-vu
else
if BOXMODEL_VUUNO4KSE
SUBDIRS += \
	stb-startup-vu
else
if BOXMODEL_VUZERO4K
SUBDIRS += \
	stb-startup-vu
else
if BOXMODEL_VUULTIMO4K
SUBDIRS += \
	stb-startup-vu
else
SUBDIRS += \
	stb-startup \
	stb-backup
endif
endif
endif
endif
endif
endif
endif

#if BOXTYPE_ARMBOX
#SUBDIRS += \
#	stb-startup-ddt \
#	stb-backup
#endif
