# Step 2: Update prequisites and commands for the build target

# 	The prerequisites are file names, separated by spaces.
# These files need to exist before the commands for the target are run.
build: my_lib.o main.o
	g++ main.o my_lib.o -o main

main.o:
	g++ main.cc -c

my_lib.o:
	g++ my_lib.cc -c

execute:
	./main

clean:
	rm -f *.o
	rm -f main
