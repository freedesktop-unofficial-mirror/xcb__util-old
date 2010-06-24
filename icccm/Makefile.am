
MAINTAINERCLEANFILES = Makefile.in

lib_LTLIBRARIES = libxcb-icccm.la

xcbinclude_HEADERS = xcb_icccm.h

AM_CFLAGS = $(CWARNFLAGS)

libxcb_icccm_la_SOURCES = icccm.c
libxcb_icccm_la_CPPFLAGS = $(XCB_CFLAGS) $(XPROTO_CFLAGS)
libxcb_icccm_la_LIBADD = $(XCB_LIBS) $(XPROTO_LIBS)
libxcb_icccm_la_LDFLAGS = -version-info 3:0:0

pkgconfig_DATA = xcb-icccm.pc

EXTRA_DIST = xcb-icccm.pc.in
