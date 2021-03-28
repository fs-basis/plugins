AC_INIT([tuxbox-plugins], [0.0.1])
AM_INIT_AUTOMAKE
m4_ifdef([AM_SILENT_RULES], [AM_SILENT_RULES])
AC_CONFIG_MACRO_DIR([m4])
AC_GNU_SOURCE

TUXBOX_APPS
TUXBOX_APPS_DIRECTORY
TUXBOX_BOXTYPE

AC_PROG_CC
AC_PROG_CXX
PKG_PROG_PKG_CONFIG
## both disabled => libtool still defaults to static
##                  at least the libtool I tested with ;-)
## --enable-shared => build only shared
## --enable-shared --enable-static => build both
AC_DISABLE_STATIC
AC_SYS_LARGEFILE
AC_PROG_LIBTOOL

PKG_CHECK_MODULES(CURL,libcurl)
PKG_CHECK_MODULES(FREETYPE,freetype2)
PKG_CHECK_MODULES(PNG,libpng)

AC_OUTPUT([
Makefile
include/Makefile
input/Makefile
getrc/Makefile
fx2/Makefile
fx2/lemm/Makefile
fx2/master/Makefile
fx2/pac/Makefile
fx2/tank/Makefile
fx2/yahtzee/Makefile
fx2/lib/Makefile
fx2/mines/Makefile
fx2/outdoor/Makefile
fx2/snake/Makefile
fx2/sokoban/Makefile
fx2/tetris/Makefile
fx2/vierg/Makefile
fx2/sol/Makefile
fx2/sudoku/Makefile
fx2/solitair/Makefile
stb-startup/Makefile
stb-startup-ddt/Makefile
stb-backup/Makefile
stb-startup-vu/Makefile
stb-switch-rc/Makefile
])
