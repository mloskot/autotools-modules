## Process this file with automake to produce Makefile.in
## Created by Anjuta
SUBDIRS = src 

autoconf_modules_testdocdir = ${prefix}/doc/autoconf_modules_test
autoconf_modules_testdoc_DATA = \
    AUTHORS \
    README \
    COPYING \
    ChangeLog \
    NEWS

EXTRA_DIST = $(autoconf_modules_testdoc_DATA)

# Remove doc directory on uninstall
uninstall-local:
	-rm -r $(autoconf_modules_testdocdir)
