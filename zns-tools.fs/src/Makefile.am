## Makefile.am

AM_CPPFLAGS = -I$(top_srcdir)/include
AM_CFLAGS = -O2 -Wall -Wextra -g -Wunused-parameter
sbin_PROGRAMS = zns.fiemap zns.segmap zns.imap

zns_fiemap_SOURCES = fiemap.c fiemap.h
zns_fiemap_LDADD = $(top_srcdir)/lib/libzns-tools.la $(top_srcdir)/lib/libf2fs.la $(top_srcdir)/lib/libjson.la

zns_segmap_SOURCES = segmap.c segmap.h
zns_segmap_LDADD = $(top_srcdir)/lib/libzns-tools.la $(top_srcdir)/lib/libf2fs.la $(top_srcdir)/lib/libjson.la

zns_imap_SOURCES = imap.c imap.h
zns_imap_LDADD = $(top_srcdir)/lib/libzns-tools.la $(top_srcdir)/lib/libf2fs.la $(top_srcdir)/lib/libjson.la
