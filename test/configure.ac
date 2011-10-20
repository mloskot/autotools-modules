dnl Process this file with autoconf to produce a configure script.
dnl Created by Anjuta application wizard.
AC_INIT([autoconf_modules_test], [1.0], [mateusz@loskot.net])
m4_ifdef([AM_SILENT_RULES],[AM_SILENT_RULES([yes])])
AM_INIT_AUTOMAKE(AC_PACKAGE_NAME, AC_PACKAGE_VERSION)
AC_CONFIG_HEADERS([config.h])
AM_MAINTAINER_MODE

AC_PROG_CXX

AX_LIB_GDAL([1.8.0])

AC_OUTPUT([
    Makefile
    src/Makefile
])

echo
echo "********* Test summary *********"
echo
echo "*** GDAL variables set by configure:"
echo "GDAL_VERSION=$GDAL_VERSION"
echo "GDAL_CFLAGS=$GDAL_CFLAGS"
echo "GDAL_LDFLAGS=$GDAL_LDFLAGS"
echo "GDAL_DEP_LDFLAGS=$GDAL_DEP_LDFLAGS"
echo "GDAL_OGR_ENABLED=$GDAL_OGR_ENABLED"
echo
echo "*** GDAL preprocessor definitions generated in config.h:"
have_gdal=`cat config.h | grep HAVE_GDAL`
echo "$have_gdal"
echo
