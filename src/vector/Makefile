#
# Makefile to build vector module
# $Id: Makefile,v 1.1 2005-02-19 21:29:20 crueda Exp $
#
#
VECTOR_INCLUDE=-I/usr/local/include  -I/usr/local/include/libshp
POLY_INCLUDE=-I../polygon/

CXXFLAGS = \
		   -g -Wall \
		   $(VECTOR_INCLUDE) \
		   $(POLY_INCLUDE)

all: Vector_ogr.o Vector_shapelib.o

.cc.o:
	g++ $(CXXFLAGS) -c $<

