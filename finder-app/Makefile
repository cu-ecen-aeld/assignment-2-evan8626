cc = $(CROSS_COMPILE)gcc
Cflags = -g -Wall
file = writer

.PHONY: all clean

$(file):
	$(cc) $(Cflags) $(INCLUDES) -o $(file) $(file).c
	
clean all: 
	rm -f $(file)
