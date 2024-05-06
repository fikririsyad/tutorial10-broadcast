# Tutorial 10
Fikri Risyad Indratno</br>
2206031170</br>
Advanced Programming B</br>

---

## Reflection

### Original code

![](images/img1.png)

How to run:
- For server, run `cargo run --bin server`
- For client, run `cargo run --bin client`

First, we run a server and three clients that will connect to the same port as the server. The server will print a message if a client has successfully connected. When we enter a message in the client's terminal, the message will be sent to the server and the server will broadcast it to all clients that are connected.

### Modify port

![](images/img2.png)

Modify the port to be 8080 in the client.

![](images/img3.png)

Modify the port to be 8080 in the server.

![](images/img4.png)

The programs run properly.

### Small changes

![](images/img5.png)
![](images/img6.png)

I've made changes that make the server's broadcast send the client's IP and port in addition to the text messages.

![](images/img7.png)