include $(top_srcdir)/globals.mk

if HAVE_OSX
noinst_LTLIBRARIES = libcoreaudiolayer.la
libcoreaudiolayer_la_SOURCES = osx/corelayer.cpp osx/corelayer.h osx/audiodevice.cpp osx/audiodevice.h
endif

if HAVE_IOS
noinst_LTLIBRARIES = libcoreaudiolayer.la
libcoreaudiolayer_la_SOURCES = ios/corelayer.cpp ios/corelayer.h
endif

libcoreaudiolayer_la_CXXFLAGS = -I$(top_srcdir)/src
