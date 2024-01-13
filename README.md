# 🌌 Gohole - Secure File Transfer in Go

Gohole is a fast, secure, and easy-to-use file transfer tool, inspired by Wormhole, written in Go! It lets you effortlessly send files and text from one device to another with end-to-end encryption. 🛡️

## Features

- 🚀 **Fast Transfers**: Quick and efficient file transfers, leveraging Go's concurrency.
- 🔒 **End-to-End Encryption**: Your files are secure during transit.
- 📁 **File & Text Sharing**: Share files or text snippets easily.
- 👥 **Concurrent Transfers**: Handle multiple transfers simultaneously.
- 🌐 **Cross-Platform**: Works on any platform that supports Go.
- 🖥️ **CLI & GUI**: Accessible through a command-line interface, GUI in the works!
- 📦 **Easy to Use**: Simple setup and user-friendly interface.

## Getting Started

1. **Install Go** (if not already installed):
   ```
   https://golang.org/dl/
   ```

2. **Clone Gohole**:
   ```
   git clone https://github.com/your-repo/Gohole.git
   ```

3. **Navigate to Gohole directory**:
   ```
   cd Gohole
   ```

4. **Build and Run Server**:
   ```
   go build -o gohole-server ./cmd/server/
   ./gohole-server
   ```

5. **Build and Run Client** (in a new terminal):
   ```
   go build -o gohole-client ./cmd/client/
   ./gohole-client
   ```

## How to Use

- To send a file or text, use the client to initiate a transfer.
- The server will provide a unique code for each transfer.
- Enter this code on the receiving end to start the transfer.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests. 🤝

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Acknowledgements

- Inspired by Wormhole 🪱
- Built with ❤️ in Go
