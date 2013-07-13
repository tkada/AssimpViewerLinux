
# ---------------------------------------------------------------------------
# Makefile for assimp/Sample_SimpleOpenGL
# aramis_acg@users.sourceforge.net
#
# Usage: make <target> <macros>

# TARGETS:
#   all                  Build the sample + assimp itself
#   clean                Cleanup all object files
# ---------------------------------------------------------------------------

VPATH = ./usr/include/

# Include flags for gcc
INCLUDEFLAGS = -I/usr/local/include

# Library flags for gcc
LIBFLAGS = -L/usr/local/lib

# Output name of executable
OUTPUT = samplegl

all:	$(OBJECTS)
#	cd ../../code/ && $(MAKE) static 
	gcc -g -o $(OUTPUT) $(INCLUDEFLAGS) -s Sample_SimpleOpenGL.cpp $(LIBFLAGS) -Wl,-Bstatic -Wl,-Bdynamic -lstdc++ -lglut -lassimp -lGL -lGLU -lIL
.PHONY: clean
clean:
	-rm $(OUTPUT)
