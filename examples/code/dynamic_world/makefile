CXX=		g++
CXXFLAGS=	-g -Wall -std=c++1y

TARGET = dynamic_world
SRC = dynamic_world.cpp
DEPS =

exec: dynamic_world makefile
	$(CXX) $(CXXFLAGS) -o $(TARGET) $(SRC)

clean:
	rm -rf *.o $(TARGET) $(TARGET).dSYM
