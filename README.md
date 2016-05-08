# A UDP proxy that drops packets

Installing deps:

    go get -t

Running the example server (with debug output):

    go run main.go -P 6121 -v 3

The server then accepts connections on port 6667.
