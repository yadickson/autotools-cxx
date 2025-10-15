AC_PREREQ(2.57)
AC_INIT([example], [0.0.1], [maintainer@example.com])

AC_LANG(C++)
AC_PROG_CXX
AC_PROG_INSTALL

AC_CANONICAL_BUILD
AC_CANONICAL_HOST

AC_CONFIG_MACRO_DIR([m4])

AC_CONFIG_HEADERS([config.h])

AC_CONFIG_FILES([
	Makefile
	src/Makefile
	test/Makefile
])

AC_CHECK_HEADER([ncurses.h])
AC_CHECK_HEADER([clocale])
AC_CHECK_HEADER([iostream])
AC_CHECK_HEADER([cstdlib])
AC_CHECK_HEADER([cstddef])

AM_INIT_AUTOMAKE([gnu foreign -Wall -Werror])

PKG_PROG_PKG_CONFIG

AC_OUTPUT