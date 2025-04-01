#
# Linux makefile
#

CFLAGS+=`sdl-config --cflags`
PREFIX=../linux/
SUFFIX=
LIBS+=`sdl-config --libs`

include makefile.common

install: $(PREFIX)gt2stereo $(PREFIX)ins2snd2 $(PREFIX)mod2sng2 $(PREFIX)ss2stereo
	install $? /usr/local/bin
