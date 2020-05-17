AM_CPPFLAGS = -D__STDC_INT64__

#include Makefile-LIBADD.inc
dist_bin_SCRIPTS = libisqrt_config isqrt_test_config

lib_LTLIBRARIES =
bin_PROGRAMS    =

lib_LTLIBRARIES += libisqrt.la
#libisqrt_la_LIBADD = $(LIBISQRT_LIBADD)
libisqrt_la_LIBADD = @LIBISQRT_LIBADD@
include_HEADERS = isqrt.h

bin_PROGRAMS += isqrt-test
#isqrt_test_LDADD = libisqrt.la $(LIBISQRT_LIBADD)
#isqrt_test_LDADD = $(ISQRT_TEST_LIBADD)
isqrt_test_LDADD = @ISQRT_TEST_LIBADD@
#isqrt_test_LDFLAGS = @ISQRT_TEST_LIBADD@
#isqrt_test_LDADD = -lisqrt $(LIBISQRT_LIBADD)
#EXTRA_isqrt_test_DEPENDENCIES = -lisqrt
EXTRA_isqrt_test_DEPENDENCIES = libisqrt.la
#isqrt_test_DEPENDENCIES = libisqrt.la
#isqrt_test_DEPENDENCIES = -lisqrt
