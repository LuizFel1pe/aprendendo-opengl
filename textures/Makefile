CPP=g++
ARGS=-std=c++17
LINUX_FLAGS=-lglfw -lGL -lX11 -lpthread -lXrandr -lXi -ldl

all: 
	$(CPP) $(ARGS) $(LINUX_FLAGS) ./src/main.cpp \
		./src/shaders/shader.cpp \
		./src/vendor/stb_image.cpp \
		./src/glad.c -o main