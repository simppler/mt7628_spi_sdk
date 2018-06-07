EXEC = socket_daemon
# build socket_daemon executable when user executes "make"  
      
socket_daemon: socket_daemon.o  
	$(CC) $(LDFLAGS) socket_daemon.o -o socket_daemon  
      
socket_daemon.o: socket_daemon.c  
	$(CC) $(CFLAGS) -c socket_daemon.c  
      
# remove object files and executable when user executes "make clean"  
clean:  
	rm *.o socket_daemon  
