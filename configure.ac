AC_PREREQ([2.57])
AC_INIT(xbitmaps, [1.0.1], [https://bugs.freedesktop.org/enter_bug.cgi?product=xorg], xbitmaps)
AM_INIT_AUTOMAKE([dist-bzip2])
AM_MAINTAINER_MODE

# Require xorg-macros: XORG_CHANGELOG
m4_ifndef([XORG_MACROS_VERSION], [AC_FATAL([must install xorg-macros 1.2 or later before running autoconf/autogen])])
XORG_MACROS_VERSION(1.2)

AM_CONFIG_HEADER(config.h)

XORG_RELEASE_VERSION
XORG_CHANGELOG

AC_OUTPUT([
	Makefile
	xbitmaps.pc
])
