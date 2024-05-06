# Tutorial 10
Fikri Risyad Indratno</br>
2206031170</br>
Advanced Programming B</br>

---

## Reflection

![](images/img1.png)

How to run:
- For server, run `cargo run --bin server`
- For client, run `cargo run --bin client`

First, we run a server and three clients that will connect to the same port as the server. The server will print a message if a client has successfully connected. When we enter a message in the client's terminal, the message will be sent to the server and the server will broadcast it to all clients that are connected.