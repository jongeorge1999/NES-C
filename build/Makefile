windows:
	gcc -I ../src/include -L ../src/lib -o main_windows ../src/main.c ../src/window.c ../src/graphicstest.c -lmingw32 -lSDL2main -lSDL2 -lSDL2_image -lm
linux:
	gcc main.c window.c -g -pedantic -o main_linux -lSDL2main -lSDL2 -lm
