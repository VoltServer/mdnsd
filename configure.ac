# Use v2.61 for backwards compat with Ubuntu 12.04 LTS
AC_PREREQ([2.61])
AC_INIT(mdnsd, 0.8-dev, https://github.com/troglobit/mdnsd/issues)
AM_INIT_AUTOMAKE([1.11 foreign no-dist-gzip dist-xz])
AM_SILENT_RULES([yes])

AC_CONFIG_SRCDIR(src/mdnsd.c)
AM_CONFIG_HEADER(config.h)
AC_CONFIG_FILES([Makefile libmdnsd/Makefile src/Makefile])
AC_CONFIG_MACRO_DIR([m4])

AC_PROG_CC
AM_PROG_AR
LT_INIT

AC_HEADER_STDC
AC_C_CONST

AC_OUTPUT
