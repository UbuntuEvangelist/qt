#############################################################################
# Makefile for building: examples
# Generated by qmake (1.07a) (Qt 3.3.4) on: Mon Dec 19 06:46:33 2005
# Project:  examples.pro
# Template: app
# Command: $(QMAKE) -o Makefile examples.pro
#############################################################################

####### Compiler, tools and options

CC       = gcc
CXX      = g++
LEX      = flex
YACC     = yacc
CFLAGS   = -pipe -Wall -W -O2 -D_REENTRANT  -DQT_NO_DEBUG -DQT_THREAD_SUPPORT -DQT_SHARED -DQT_TABLET_SUPPORT
CXXFLAGS = -pipe -Wall -W -O2 -D_REENTRANT  -DQT_NO_DEBUG -DQT_THREAD_SUPPORT -DQT_SHARED -DQT_TABLET_SUPPORT
LEXFLAGS = 
YACCFLAGS= -d
INCPATH  = -I/usr/share/qt3/mkspecs/default -I. -I. -I/usr/include/qt3 -I/home/mascix/Desktop/tmp/f4l-0.2/src/flagStonePort/transform-cxx-bsd -I/home/mascix/Desktop/tmp/f4l-0.2/src/flagStonePort/transform-util-cxx
LINK     = g++
LFLAGS   = 
LIBS     = $(SUBLIBS) -L/home/mascix/Desktop/tmp/f4l-0.2/src/flagStonePort/transform-cxx-bsd/transform -ltransform -L/usr/share/qt3/lib -L/usr/X11R6/lib -lqt-mt -lXext -lX11 -lm -lpthread -L/home/mascix/Desktop/tmp/f4l-0.2/src/flagStonePort/transform-util-cxx/transform-util/ -ltransform-util
AR       = ar cqs
RANLIB   = 
MOC      = /usr/share/qt3/bin/moc
UIC      = /usr/share/qt3/bin/uic
QMAKE    = qmake
TAR      = tar -cf
GZIP     = gzip -9f
COPY     = cp -f
COPY_FILE= $(COPY)
COPY_DIR = $(COPY) -r
INSTALL_FILE= $(COPY_FILE)
INSTALL_DIR = $(COPY_DIR)
DEL_FILE = rm -f
SYMLINK  = ln -sf
DEL_DIR  = rmdir
MOVE     = mv -f
CHK_DIR_EXISTS= test -d
MKDIR    = mkdir -p

####### Output directory

OBJECTS_DIR = ./

####### Files

HEADERS = BasicButtons.hpp \
		BasicShapes.hpp \
		BasicSounds.hpp \
		DrawingShapes.hpp \
		functions.h \
		ShowFontFile.hpp \
		ShowImage.hpp \
		StreamingSounds.hpp
SOURCES = functions.cpp \
		main.cpp
OBJECTS = functions.o \
		main.o
FORMS = 
UICDECLS = 
UICIMPLS = 
SRCMOC   = 
OBJMOC = 
DIST	   = examples.pro
QMAKE_TARGET = examples
DESTDIR  = 
TARGET   = examples

first: all
####### Implicit rules

.SUFFIXES: .c .o .cpp .cc .cxx .C

.cpp.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o $@ $<

.cc.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o $@ $<

.cxx.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o $@ $<

.C.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o $@ $<

.c.o:
	$(CC) -c $(CFLAGS) $(INCPATH) -o $@ $<

####### Build rules

all: Makefile $(TARGET)

$(TARGET):  $(UICDECLS) $(OBJECTS) $(OBJMOC)  
	$(LINK) $(LFLAGS) -o $(TARGET) $(OBJECTS) $(OBJMOC) $(OBJCOMP) $(LIBS)

mocables: $(SRCMOC)
uicables: $(UICDECLS) $(UICIMPLS)

$(MOC): 
	( cd $(QTDIR)/src/moc && $(MAKE) )

Makefile: examples.pro  /usr/share/qt3/mkspecs/default/qmake.conf /usr/share/qt3/lib/libqt-mt.prl
	$(QMAKE) -o Makefile examples.pro
qmake: 
	@$(QMAKE) -o Makefile examples.pro

dist: 
	@mkdir -p .tmp/examples && $(COPY_FILE) --parents $(SOURCES) $(HEADERS) $(FORMS) $(DIST) .tmp/examples/ && ( cd `dirname .tmp/examples` && $(TAR) examples.tar examples && $(GZIP) examples.tar ) && $(MOVE) `dirname .tmp/examples`/examples.tar.gz . && $(DEL_FILE) -r .tmp/examples

mocclean:

uiclean:

yaccclean:
lexclean:
clean:
	-$(DEL_FILE) $(OBJECTS)
	-$(DEL_FILE) *~ core *.core


####### Sub-libraries

distclean: clean
	-$(DEL_FILE) $(TARGET) $(TARGET)


FORCE:

####### Compile

functions.o: functions.cpp 

main.o: main.cpp functions.h \
		BasicButtons.hpp \
		BasicShapes.hpp \
		BasicSounds.hpp \
		ShowFontFile.hpp \
		ShowImage.hpp \
		StreamingSounds.hpp

####### Install

install:  

uninstall:  

