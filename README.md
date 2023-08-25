===========================terminal base chatting program========================

The program is a simple command line interface chat room using socket programming.
Multiple clients can connect and send/receive messages in the room,
The GUI of the program is under developing with Django Rest Framework
to know how it works, kindly look up the screenshort in Image directory
How to work with it.





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
License

T