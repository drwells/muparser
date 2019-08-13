lib_LTLIBRARIES = libmuparser.la

libmuparser_la_SOURCES = $(top_srcdir)/src/muParser.cpp \
$(top_srcdir)/src/muParserBase.cpp                      \
$(top_srcdir)/src/muParserBytecode.cpp                  \
$(top_srcdir)/src/muParserDLL.cpp                       \
$(top_srcdir)/src/muParserError.cpp                     \
$(top_srcdir)/src/muParserInt.cpp                       \
$(top_srcdir)/src/muParserTest.cpp                      \
$(top_srcdir)/src/muParserTokenReader.cpp

include_HEADERS = $(top_srcdir)/include/muParser.h \
$(top_srcdir)/include/muParserBase.h               \
$(top_srcdir)/include/muParserBytecode.h           \
$(top_srcdir)/include/muParserCallback.h           \
$(top_srcdir)/include/muParserDLL.h                \
$(top_srcdir)/include/muParserDef.h                \
$(top_srcdir)/include/muParserError.h              \
$(top_srcdir)/include/muParserFixes.h              \
$(top_srcdir)/include/muParserInt.h                \
$(top_srcdir)/include/muParserStack.h              \
$(top_srcdir)/include/muParserTemplateMagic.h      \
$(top_srcdir)/include/muParserTest.h               \
$(top_srcdir)/include/muParserToken.h              \
$(top_srcdir)/include/muParserTokenReader.h

AM_CXXFLAGS=-I$(top_srcdir)/include/
