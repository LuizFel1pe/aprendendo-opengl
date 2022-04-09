CPP=g++
ARGS=-std=c++17
LINUX_FLAGS=-lglfw -lGL -lX11 -lpthread -lXrandr -lXi -ldl

all: 
	$(CPP) $(ARGS) $(LINUX_FLAGS) ./src/main.cpp ./src/shader.cpp ./src/glad.c -o main
