## Process this file with automake to produce Makefile.in

AM_CPPFLAGS = \
	@GTK_CFLAGS@ @STLPORT_CXXFLAGS@

bin_PROGRAMS = mmrun

mmrun_SOURCES = \
	gtkcompletionline.cc gtkcompletionline.h \
	history.cc history.h \
	main.cc main.h \
	prefs.cc prefs.h ci_string.h

# gmrun_LDFLAGS = -s

mmrun_LDADD = @GTK_LIBS@ @STLPORT_LDFLAGS@

