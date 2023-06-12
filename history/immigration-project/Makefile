SRC = story.md
BIN = story.pdf
BROWSER = brave-browser

$(BIN): $(SRC)
	pandoc -o $(BIN) $(SRC)

clean:
	rm $(BIN)

display: $(BIN)
	$(BROWSER) $(BIN)

.PHONY: clean display
