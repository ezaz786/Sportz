##########################################################
# 		                                         #
#							 #
##########################################################


SRCDIR = ../src
INCLUDEDIR = ../include
OBJDIR = ../obj
BINDIR = ../bin
CFLAGS = -c -g -Wall -I${INCLUDEDIR}


all:
	gcc ${CFLAGS}  ${SRCDIR}/main.c -o ${OBJDIR}/main.o
	gcc ${OBJDIR}/main.o -o ${BINDIR}/Sportz.bin


clean:

	rm ${OBJDIR}/main.o -o ${BINDIR}/Sportz.bin


#################### End of Makefile #####################
