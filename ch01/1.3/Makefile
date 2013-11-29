myls:myls.o
	gcc -o myls myls.o -L../../lib -lerr
myls.o:../../include/apue.h

cl:
	rm myls.o
tag:
	ctags -R --field=+lS	
