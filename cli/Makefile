CC= g++
CPPFLAGS= -std=c++11 -fopenmp -lm -O3
OBJS= deepwalk line walklets hpe
LIBS= -L ../bin -lproNet

all: $(OBJS)

$(OBJS):
	$(CC) $(CPPFLAGS) $@.cpp $(LIBS) -o $@
clean:
	rm $(OBJS)
