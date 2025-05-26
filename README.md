# Chat-Application
# 💬 Java Swing Chat Client

A simple yet functional **Client Chat Application** built using **Java Swing** and **Sockets** for real-time communication with a server.

![Java Chat GUI Screenshot](assets/client-screenshot.png) <!-- Replace with actual screenshot path -->

---

## 🚀 Features

- 📡 Connects to a server via TCP socket
- 💬 Real-time messaging interface
- 🖼️ Intuitive GUI with custom fonts and icons
- 🧵 Multi-threaded: read and write messages concurrently
- 🔒 Gracefully handles exit conditions and connection loss
- ✅ Cross-platform (runs anywhere Java is supported)

---

## 🖥️ GUI Overview

- **Top Section**: Header with logo and "Client Area" label
- **Middle Section**: Scrollable area showing messages
- **Bottom Section**: Text field for typing and sending messages

---

## 🛠️ Getting Started

### Prerequisites

- Java 8 or later installed
- A running Java-based server (see [Java Chat Server](#-server-code))

### 🧪 Cloning & Running

```bash
git clone https://github.com/yourusername/java-swing-chat-client.git
cd java-swing-chat-client
javac Client.java
java Client
### PROJECT STRUCTURE
.
├── Client.java              # Main client application
├── assets/
│   └── cc.png               # Logo/icon used in the GUI (replaceable)
└── README.md
