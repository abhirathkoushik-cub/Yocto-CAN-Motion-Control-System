TARGET5 = rx_client
TARGET6 = tx_server

all: $(TARGET5) $(TARGET6)


$(TARGET5): $(TARGET5).c
	$(CC) $(CFLAGS) $(LDFLAGS) -o $@ $<


$(TARGET6): $(TARGET6).c
	$(CC) $(CFLAGS) $(LDFLAGS) -o $@ $<

clean:
	rm -f $(TARGET5) $(TARGET6)
