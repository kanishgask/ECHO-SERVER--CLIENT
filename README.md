**# Echo Client-Server TCP Socket Application in Java**

# Echo Client-Server TCP Socket Application in Java

## 📝 Project Overview

This project demonstrates a simple **Echo Client-Server application** implemented using **TCP sockets in Java**. The server listens for incoming messages from the client, and echoes the same message back to the client. Communication continues until the keyword `"stop"` is sent.

---

## 🎯 Aim

To implement an echo client and echo server application using **Java TCP sockets**, where the client sends messages to the server and receives the same messages echoed back.

---

## 🔁 Workflow

1. Server starts and waits for a client to connect.
2. Client connects to the server.
3. Messages are exchanged using `DataInputStream` and `DataOutputStream`.
4. Communication continues until either side sends `"stop"`.
5. All streams and sockets are closed gracefully.

---

## 📁 Files Included

- `EchoServer.java` — Java file containing the echo server logic.
- `EchoClient.java` — Java file containing the echo client logic.
- `README.md` — This documentation file.

---

## 🧠 Algorithm

### 🔹 Echo Server
1. Create a `ServerSocket` on port 6666.
2. Accept the client connection.
3. Use `DataInputStream` to read client messages.
4. Use `DataOutputStream` to send back (echo) the same message.
5. Repeat until the message is `"stop"`.
6. Close all resources.

### 🔹 Echo Client
1. Create a `Socket` to connect to the server (`localhost`, port 6666).
2. Use `DataOutputStream` to send messages to the server.
3. Use `DataInputStream` to read echoed messages from the server.
4. Repeat until the message is `"stop"`.
5. Close all resources.

---

## 💻 How to Run

### 1. Compile the Code

```bash
javac EchoServer.java
javac EchoClient.java


This project demonstrates a simple **Echo Client-Server application** implemented using **TCP sockets in Java**. The server listens for incoming messages from the client, and echoes the same message back to the client. Communication continues until the keyword `"stop"` is sent.

---

## 🎯 Aim

To implement an echo client and echo server application using **Java TCP sockets**, where the client sends messages to the server and receives the same messages echoed back.

---

## 🔁 Workflow

1. Server starts and waits for a client to connect.
2. Client connects to the server.
3. Messages are exchanged using `DataInputStream` and `DataOutputStream`.
4. Communication continues until either side sends `"stop"`.
5. All streams and sockets are closed gracefully.

---

## 📁 Files Included

- `EchoServer.java` — Java file containing the echo server logic.
- `EchoClient.java` — Java file containing the echo client logic.
- `README.md` — This documentation file.

---

## 🧠 Algorithm

### 🔹 Echo Server
1. Create a `ServerSocket` on port 6666.
2. Accept the client connection.
3. Use `DataInputStream` to read client messages.
4. Use `DataOutputStream` to send back (echo) the same message.
5. Repeat until the message is `"stop"`.
6. Close all resources.

### 🔹 Echo Client
1. Create a `Socket` to connect to the server (`localhost`, port 6666).
2. Use `DataOutputStream` to send messages to the server.
3. Use `DataInputStream` to read echoed messages from the server.
4. Repeat until the message is `"stop"`.
5. Close all resources.

---

## 💻 How to Run

### 1. Compile the Code

```bash
javac EchoServer.java
javac EchoClient.java



**  OUTPUT:**
SERVER OUTPUT:
![image](https://github.com/user-attachments/assets/b9501c91-05cd-4f5a-b938-d9c82cc50d0e)

CLIENT OUTPUT:
![image](https://github.com/user-attachments/assets/ad6ad15d-0481-4181-bdf0-3611e54eb567)

