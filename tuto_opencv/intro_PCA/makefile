CC = gcc
CXX = g++
RM = rm -f
CPPFLAGS = -Wall -g 
LDFLAGS = -g 
LDLIBS = -lopencv_imgcodecs -lopencv_imgproc -lopencv_core -lopencv_highgui -lopencv_videoio

SRCS = introduction_pca.cpp
OBJS = $(subst .cpp,.o,$(SRCS))

TARGET = program

all: $(TARGET)

$(TARGET): $(OBJS)
	$(CXX) $(LDFLAGS) -o $(TARGET).exe $(OBJS) $(LDLIBS)

$(TARGET).o: $(TARGET).o

clean:
	$(RM) $(OBJS)

deepclean: clean
	$(RM) $(TARGET).exe
