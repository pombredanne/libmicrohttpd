man_MANS = libmicrohttpd.3

SUBDIRS = . examples

DISTCLEANFILES = \
  libmicrohttpd.cps \
  libmicrohttpd.dvi \
  libmicrohttpd-tutorial.cps \
  libmicrohttpd-tutorial.dvi
info_TEXINFOS = \
  libmicrohttpd.texi \
  libmicrohttpd-tutorial.texi
microhttpd_TEXINFOS = \
  chapters/basicauthentication.inc \
  chapters/bibliography.inc \
  chapters/exploringrequests.inc \
  chapters/hellobrowser.inc \
  chapters/introduction.inc \
  chapters/largerpost.inc \
  chapters/processingpost.inc \
  chapters/responseheaders.inc \
  chapters/tlsauthentication.inc \
  chapters/sessions.inc \
  fdl-1.3.texi \
  lgpl.texi \
  ecos.texi

EXTRA_DIST = $(man_MANS) Doxyfile $(microhttpd_TEXINFOS)
