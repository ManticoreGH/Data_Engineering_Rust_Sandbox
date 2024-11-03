# Makefile for Rust project

# Variables
CARGO := cargo

# Targets
.PHONY: all format lint test build clean

all: format lint test build

format:
	$(CARGO) fmt

lint:
	$(CARGO) clippy -- -D warnings

test:
	$(CARGO) test

build:
	$(CARGO) build --release

clean:
	$(CARGO) clean