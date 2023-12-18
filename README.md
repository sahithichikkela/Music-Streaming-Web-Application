# 🎵 Spotify Clone

## 📌 Objectives

This project demonstrates the application of several core software engineering concepts:

* Object-Oriented Programming (OOP)
* Database design and management
* Multithreading
* Socket programming
* Data encryption
* Graphical User Interface (GUI) development using JavaFX

---

## 🧰 Prerequisites

Ensure the following are installed on your system:

* Java
* SQLite
* JavaFX
* NetBeans or IntelliJ IDEA (IDE)
* Ant or Gradle (build system)

---

## ⚙️ Implementation

The project is structured into three main components:

1. **SpotifyClient**
2. **SpotifyServer**
3. **Sockets**

### 📱 SpotifyClient

This module represents the client-side application. It is responsible for:

* Accepting user input
* Sending requests to the server via sockets
* Receiving and displaying server responses

---

### 🖥️ SpotifyServer

The server processes requests received from clients. It:

* Handles client communication
* Interacts with the database using the `DBManager` class
* Responds to client requests accordingly

The server is **multithreaded**, allowing it to manage multiple client requests simultaneously. Server activity is logged and displayed in the terminal for monitoring purposes.

---

### 🔌 Sockets

All communication between the client and the server is handled through socket programming. Each client communicates with the server using a dedicated socket connection, through which requests are sent and responses are returned.

---

## 🎨 GUI Development

The graphical user interface is built using **JavaFX**.

Learn more about JavaFX here:
🔗 [https://en.wikipedia.org/wiki/JavaFX](https://en.wikipedia.org/wiki/JavaFX)

---

## ▶️ How to Run the Project

1. Switch to the `netbeans` branch.
2. Clone the `SpotifyServer` and `SpotifyClient` directories to your local machine.
3. Open both projects in **NetBeans**.
4. Run the `SpotifyServer` first.

   * Wait until you see the message: **`Listening...`**
5. Run the `SpotifyClient`.

   * A window will appear displaying the login screen.
6. The application is now ready to use 🚀
