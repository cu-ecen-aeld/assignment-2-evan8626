cc = $(CROSS_COMPILE)gcc
Cflags = -g 
file = writer

.PHONY: all clean

$(file):
	$(cc) $(Cflags) -o $(file) $(file).c
	
clean all: 
	rm -f $(file)
