
Socket-based Chat Program

A simple chat program implemented in Python using socket programming. This program allows multiple clients to communicate with each other through a central server.
Getting Started
Prerequisites

    Python 3.x

Installation

Clone the repository:

https://github.com/ethic-bakeery/rafsan.git

Run the server:

python server.py

Run multiple client sessions in separate terminal windows:


    python client.py

    Follow the on-screen instructions to enter your nickname for each client session.

    Start chatting!

Features

    Multiple clients can join the chat.
    Clients can send messages that are broadcasted to all connected clients.
    Each client session is identified by a unique nickname.

Usage

    Run the server using python server.py.

    In separate terminal windows, run the client program using python client.py.

    For each client, enter a unique nickname when prompted.

    Start sending and receiving messages between clients.

Commands

    /exit or /quit: Disconnect from the chat.
    /help: Display a help message with available commands.

Troubleshooting

    If the server is running on a different machine, update the SERVER_IP variable in client.py to the server's IP address.

Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

Feel free to modify and expand on this template according to the specific details of your chat program. Make sure to replace placeholder names, URLs, and descriptions with the actual information about your project.