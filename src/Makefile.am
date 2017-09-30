LIBISQRT_LIBADD = -lm

lib_LTLIBRARIES = libisqrt.la
libisqrt_la_LIBADD = $(LIBISQRT_LIBADD)
include_HEADERS = isqrt.h
bin_PROGRAMS = isqrt-test
isqrt_test_LDADD = libisqrt.la $(LIBISQRT_LIBADD)

AM_CPPFLAGS = -D__STDC_INT64__

SUBDIRS = ../glitter
AM_CPPFLAGS += ../glitter/src
