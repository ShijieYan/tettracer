all:
	nvcc -lineinfo -g -I/pub/cuda-7.5/targets/x86_64-linux/include -I../Externals -std=c++11 -O3 Main.cu -o tettracer  -lGL -lGLEW -lglfw

clean:
	@rm -rf tettracer
