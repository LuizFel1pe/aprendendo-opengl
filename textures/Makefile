CPP=g++
ARGS=-std=c++17
LINUX_FLAGS=-lglfw -lGL -lX11 -lpthread -lXrandr -lXi -ldl
ARCHIVES=./src/main.cpp ./src/shader.cpp ./src/vendor/stb_image.cpp ./src/glad.c

all: 
	$(CPP) $(ARGS) $(LINUX_FLAGS) $(ARCHIVES) -o main
