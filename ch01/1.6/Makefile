pid:pid.o
	gcc -o pid pid.o -L../../lib -lerr
pid.o:../../include/apue.h

cl:
	rm pid.o
tag:
	ctags -R --field=+lS
