subdir = src/gausskernel/storage/access/rmgrdesc
top_builddir = ../../../../..
include $(top_builddir)/src/Makefile.global

ifneq "$(MAKECMDGOALS)" "clean"
  ifneq "$(MAKECMDGOALS)" "distclean"
     ifneq "$(shell which g++ |grep hutaf_llt |wc -l)" "1"
        -include $(DEPEND)
     endif
  endif
endif
OBJS = barrierdesc.o clogdesc.o dbasedesc.o gindesc.o gistdesc.o \
	   hashdesc.o heapdesc.o motdesc.o mxactdesc.o nbtdesc.o relmapdesc.o \
	   seqdesc.o smgrdesc.o spgdesc.o standbydesc.o tblspcdesc.o \
	   xactdesc.o xlogdesc.o slotdesc.o

include $(top_srcdir)/src/gausskernel/common.mk
