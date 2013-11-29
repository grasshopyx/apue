errno:errno.o
	gcc -o errno errno.o -L../../lib -lerr
errno.o:../../include/apue.h

cl:
	rm errno.o
tag:
	ctags -R --field=+lS	
