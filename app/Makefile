#CC := arm-linux-gnueabi-gcc
CC = gcc
OBJS = test_dfs.o
CFLAGS = -Wall -g
TARGET = debugfs_read

all: $(TARGET)
$(TARGET) : $(OBJS)
	@echo -e '\n\nCompile Start...'
	$(CC) $(CFLAGS) -o $@ $(OBJS)
	@cp -f $(TARGET) ../bin/


clean:
	@echo "Cleaning...."
	rm -f $(OBJS) $(TARGET)
	rm -f ../bin/$(TARGET)

clena: clean
celan: clean
celna: clean

