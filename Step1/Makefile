# Step 1: Create a Makefile with basic target - commands syntax

# target: prerequisites (ex: build: my_lib.o main.o)
#	commands (ex: g++ main.o my_lib.o -o main)

# The commands are a series of steps typically to make the target,
# need to start with a tab character, not space
build:
	g++ main.cc -o main

execute:
	./main

# Clean is often used as a target that removes the output of other targets
clean:
	rm -f *.o
	rm -f main
