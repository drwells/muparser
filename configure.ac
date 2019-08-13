AC_INIT([muparser], [2.2.6])

AC_PREREQ([2.69])

AC_CONFIG_AUX_DIR([config])

AC_CONFIG_MACRO_DIR([m4])

AM_INIT_AUTOMAKE([1.9 foreign -Wall -Werror subdir-objects])
AM_SILENT_RULES([yes])
AM_PROG_AR

LT_INIT([])

AC_LANG(C++)
AC_PROG_CXX
AC_PROG_CXXCPP
AC_CONFIG_FILES([Makefile])

enablecxx11=yes
AX_CXX_COMPILE_STDCXX_11([],[mandatory])

AC_OUTPUT
