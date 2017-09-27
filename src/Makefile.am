lib_LTLIBRARIES = libisqrt.la
libisqrt_la_SOURCES = isqrt.c
libisqrt_la_LIBADD = -lm
include_HEADERS = isqrt.h
bin_PROGRAMS = isqrt
isqrt_SOURCES = main.c
isqrt_LDADD = libisqrt.la -lm

AM_CPPFLAGS += -D__STDC_INT64__
