noinst_LTLIBRARIES = libde265_encoder.la

libde265_encoder_la_CXXFLAGS = -I..
libde265_encoder_la_SOURCES = \
  analyze.cc analyze.h \
  encode.h encode.cc \
  encoder-params.h encoder-params.cc \
  encoder-context.h encoder-context.cc \
  encpicbuf.h encpicbuf.cc \
  sop.h sop.cc

SUBDIRS=algo
libde265_encoder_la_LIBADD = algo/libde265_encoder_algo.la
