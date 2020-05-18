AM_CPPFLAGS = -D__STDC_INT64__

lib_LTLIBRARIES =
bin_PROGRAMS    =

lib_LTLIBRARIES += libisqrt.la
libisqrt_la_CPPFLAGS = $(GLITTER_CFLAGS)
libisqrt_la_LIBADD   = $(GLITTER_LIBS) -lm
include_HEADERS = isqrt.h

bin_PROGRAMS += isqrt-test
isqrt_test_CPPFLAGS = $(GLITTER_CFLAGS)
isqrt_test_LDADD    = $(GLITTER_LIBS) -lm
EXTRA_isqrt_test_DEPENDENCIES = libisqrt.la

