CROSS_COMPILE = riscv64-unknown-linux-gnu-
CC=$(CROSS_COMPILE)gcc

CFLAGS = $(CFLAG)
LDFLAGS = $(LDFLAG)

TARGET = amp_test
OBJS = amp_test.c image.c gunzip.c

all:
	${CC} ${OBJS} $(CFLAGS) $(LDFLAGS) -Wall -g -o ${TARGET}
	@echo "Compile done."
clean:
	@rm -f *.o ${TARGET}
	@echo "Clean done."
