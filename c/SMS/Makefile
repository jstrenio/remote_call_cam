CC=g++
DLIBS=-lbcm2835 -lrt -lpthread
OBJS= wildlive.o ../arduPi.o ../sim7x00.o
SMS:$(OBJS) 
	$(CC) -Wall -o wildlive $(OBJS)  $(DLIBS) 

%.o:%.c
	$(CC) -c -o $@ $<

clean:
	rm -f *.o wildlive

