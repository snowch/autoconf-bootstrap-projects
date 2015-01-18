AC_INIT([myproject], [123], [flameeyes@flameeyes.eu], [http://blog.flameeyes.eu/tag/autotoolsmythbuster])

PKG_CHECK_MODULES([GLIB], [glib-2.0 >= 2.3.0])
AC_SUBST([GLIB_CFLAGS])
AC_SUBST([GLIB_LIBS])

AC_CONFIG_MACRO_DIR([build])
GLIB_TESTS

AM_INIT_AUTOMAKE
AC_PROG_CC
AC_OUTPUT([Makefile src/Makefile])
