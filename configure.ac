#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

AC_PREREQ([2.69])
AC_INIT([sa], [0.01], [/dev/null])
AC_CONFIG_SRCDIR([sa.c])
AC_CONFIG_HEADERS([config.h])
AC_CONFIG_MACRO_DIR([build])

AM_INIT_AUTOMAKE
AM_CFLAGS=-g -Wall -O3

# Checks for programs.
AM_PROG_CC_C_O
AC_PROG_CC_C99

# Checks for libraries.
PKG_CHECK_MODULES([json],[json])
LIBCURL_CHECK_CONFIG
AC_CHECK_DECL([LIBCURL_FEATURE_SSL])

# Checks for header files.

# Checks for typedefs, structures, and compiler characteristics.

# Checks for library functions.

AC_CONFIG_FILES([Makefile])
AC_OUTPUT
