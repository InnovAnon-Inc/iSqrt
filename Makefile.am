# Install the pkg-config file.
pkgconfigdir = $(libdir)/pkgconfig
pkgconfig_DATA = src/libisqrt.pc src/isqrt-test.pc

DISTCLEANFILES = $(pkgconfig_DATA)
EXTRA_DIST = src/libisqrt.pc.in src/isqrt-test.pc.in

SUBDIRS = src
dist_doc_DATA = README.md
ACLOCAL_AMFLAGS = -I m4

