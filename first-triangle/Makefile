CPP=g++
ARGS=-std=c++17
LINUX_FLAGS=-lglfw -lGL -lX11 -lpthread -lXrandr -lXi -ldl
ENTRYPOINT=./src/main.cpp

all: 
	$(CPP) $(ARGS) $(LINUX_FLAGS) $(ENTRYPOINT) ./src/glad.c -o main
