all:	udpclient udpserver

udpclient: udpclient.c
	gcc -Wall $< -o $@

udpserver: udpserver.c
	gcc -Wall $< -o $@

clean:
	rm -f udpclient udpserver *.o *~ core

