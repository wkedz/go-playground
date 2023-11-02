# go-playground

This repo contains some code snippets written in go. 

# Commands

  # Heap stack analyze

  go tool compile -m GO_FILE - analyze the initial code.


  go run -gcflags="-m" 
  go build -gcflags="-m" 

  # Disable DWARF (debugger) generation

  go build -ldflags=-w

# Tests

## Benchmarking

  go test -bench=.

## Coverage

  go test -cover

## Race condition

  go test -race

## More 

  go test --help