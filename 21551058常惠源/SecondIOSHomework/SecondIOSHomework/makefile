CC=clang

FRAMEWORKS:=-framework Foundation
LIBRARIES:=-lobjc

SOURCE=main.m MyCal.m Util.m

CFLAGS=-Wall -Werror -g -v $(SOURCE)
LDFLAGS=$(LIBRARIES) $(FRAMEWORKS)
OUT=-o mycal

all:
	$(CC) $(CFLAGS) $(LDFLAGS) $(OUT)
clean:
	rm mycal
	rm -rf mycal.*
