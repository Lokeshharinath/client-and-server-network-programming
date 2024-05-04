# UDP Ping Pong Program

This program has two Python scripts, `client.py` and `server.py`, to facilitate a straightforward UDP ping-pong communication.

## Prerequisites

- Python 3.x
- Standard library (`socket` module)

1. Running the Server

Navigate to the directory containing `server.py` in your terminal. Execute the following command:

python server.py <port>

2. Running the Client

Open another terminal window. Navigate to the directory containing client.py. Run the command:

bash

python client.py <hostname> <port>

Replace <hostname> with the server's hostname or IP address, and <port> with the same port number used for the server.

Example in case of my code snippet:
python client.py localhost 8008

Additional Information:
    The server responds with a 'PONG' message 70% of the time and drops the packet 30% of the time.
    Each message sent by the client has a 2-second timeout.

