# electron-bug-test-truncated-protocol-responses

```bash
# Clone this repository
git clone https://github.com/pfrazee/electron-bug-test-truncated-protocol-responses
# Go into the repository
cd electron-bug-test-truncated-protocol-responses
# Install dependencies
npm install
# Run the app
npm start
```

Then:

- The window will open with README.md rendered and devtools open. Switch to the network tab so that you can log requests. 
- Typically the request will succeed. Refresh repeatedly (`cmd/ctrl + r`) until the window becomes blank.
- Notice in the network tab, the request response is empty, though the headers are set.

## License

[CC0 1.0 (Public Domain)](LICENSE.md)
