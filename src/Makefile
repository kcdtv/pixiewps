CC = gcc
CCFLAGS = -lssl -lcrypto -Wall -Werror

TARGET = pixiewps
PREFIX = $(DESTDIR)/usr/local
BINDIR = $(PREFIX)/bin

all:
	$(CC) $(CCFLAGS) pixiewps.c -o $(TARGET)

install:
	install -D pixiewps $(BINDIR)/$(TARGET)

uninstall:
	rm $(BINDIR)/$(TARGET)

clean:
	rm -f $(TARGET)
