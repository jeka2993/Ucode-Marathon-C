all: inst

FLAGS = -Wall -Wextra -Werror -Wpedantic
CC = clang
name = playlist

inst: $(name)

$(name):
	$(CC) $(FLAGS) -o $(name) src/*.c

uninstall:
	rm $(name)

clean:
	rm -rf src
	rm -rf inc

reinstall:
	make uninstall
	make

