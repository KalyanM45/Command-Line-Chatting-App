# Socket Communication: Server-Client Messaging

This repository contains a simple Python implementation showcasing socket communication between a server and a client using threading. The code is organized into two classes, `ServerNode` and `ClientNode`, demonstrating a basic messaging system.

## ServerNode

The `ServerNode` class represents the server side of the communication. It initializes a socket, binds it to a specific IP address and port, and listens for incoming connections. Once a connection is established, it accepts it and allows for sending and receiving messages.

### Methods:

- `send_sms(SMS)`: Sends the provided SMS (Short Message Service) string to the connected client.
- `receive_sms()`: Continuously listens for incoming messages from the connected client and prints them to the console.
- `main()`: Main loop for the server, allowing the user to input messages for sending.

## ClientNode

The `ClientNode` class represents the client side of the communication. It initializes a socket and connects to the specified server's IP address and port. Similar to the server, it provides methods for sending and receiving messages.

### Methods:

- `send_sms(SMS)`: Sends the provided SMS string to the connected server.
- `receive_sms()`: Continuously listens for incoming messages from the server and prints them to the console.
- `main()`: Main loop for the client, allowing the user to input messages for sending.

## Usage:

1. Run the server script (`server.py`) in one terminal window.
2. Run the client script (`client.py`) in another terminal window.
3. Start typing messages in the client's terminal to send them to the server.
4. Messages received from the server will be displayed in the client's terminal.

## License

This project is licensed under the [GNU General Public License v3.0](LICENSE).

## Contribution Guidelines

Feel free to contribute by submitting issues or pull requests.

## Acknowledgments

- Special thanks to contributors and developers who have helped improve this project
