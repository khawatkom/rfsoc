CC=gcc
FLAGS=-Wall -O3
ARCH=arm
CROSS_COMPILE=arm-xilinx-linux-gnueabi-

####
PROG=lia_rp
EXTRA=zynq_io.c

all: $(PROG)

$(PROG): $(PROG).c $(EXTRA)
	$(CC) $(FLAGS) -o $(PROG) $(PROG).c $(EXTRA) -lm 

clean:
	rm -f $(PROG)

