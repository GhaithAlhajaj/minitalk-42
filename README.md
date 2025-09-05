# 🗣️ minitalk-42

![Minitalk Banner](https://user-images.githubusercontent.com/yourusername/minitalk_banner.png)

> **minitalk-42** is a minimalist messaging application developed as part of the 42 School curriculum. It facilitates inter-process communication using UNIX signals, enabling a client to send messages to a server.

---

## 📌 Project Overview

**minitalk-42** is designed to:

- Implement a communication protocol using UNIX signals.
- Develop a client-server model where the client sends messages to the server.
- Enhance understanding of process management and signal handling in C.

---

## ✨ Features

- **Client-Server Communication:** Utilizes UNIX signals (`SIGUSR1` and `SIGUSR2`) for message transmission.
- **Real-Time Message Display:** Server displays each received character in real-time.
- **Error Handling:** Robust error handling for invalid inputs and failed signal transmissions.
- **Bonus Features (Optional):**
  - **Acknowledgment Signals:** Server sends acknowledgment signals back to the client upon message receipt.
  - **Unicode Support:** Handles Unicode characters for international message transmission.

---

## 🛠 Technologies Used

- **Programming Language:** C
- **Signal Handling:** UNIX signals (`SIGUSR1`, `SIGUSR2`)
- **Build System:** Makefile
- **Version Control:** Git & GitHub
- **Operating Systems:** Linux (Ubuntu 22.04), macOS

---
