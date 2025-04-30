# Compiler and flags
CXX ?= g++
CXXFLAGS ?= -O2

# Source and output
SRC = hello.cpp
OUT = hello

# Default target
all: $(OUT)

# Build the binary
$(OUT): $(SRC)
	$(CXX) $(CXXFLAGS) -o $(OUT) $(SRC)

# Clean build artifacts
clean:
	rm -f $(OUT)

