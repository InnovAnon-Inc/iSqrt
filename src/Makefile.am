AM_CPPFLAGS = -D__STDC_INT64__

SUBDIRS = ../glitter
AM_CPPFLAGS += $(top_srcdir)/glitter/src

include Makefile-LIBADD.inc

lib_LTLIBRARIES = libisqrt.la
libisqrt_la_LIBADD = $(LIBISQRT_LIBADD)
include_HEADERS = isqrt.h
bin_PROGRAMS = isqrt-test
isqrt_test_LDADD = libisqrt.la $(LIBISQRT_LIBADD)
