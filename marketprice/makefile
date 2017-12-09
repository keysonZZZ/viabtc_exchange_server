TARGET  := marketprice.exe
INCS = -I ../network -I ../utils
LIBS = -L ../utils -lutils -L ../network -lnetwork -L/usr/lib/x86_64-linux-gnu -lcurl -Wl,-Bstatic -lev -ljansson -lmpdec -lrdkafka -lz -lssl -lcrypto -lhiredis -Wl,-Bdynamic -lm -lpthread -ldl
include ../makefile.inc
