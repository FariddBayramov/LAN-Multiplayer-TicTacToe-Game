# 🎮 LAN Multiplayer Tic-Tac-Toe Game

Welcome to the **LAN Multiplayer Tic-Tac-Toe Game**! This project enables players to enjoy multiplayer Tic-Tac-Toe over a secure local network (LAN) or through a wireless ad-hoc network. Built using **Python** and the **socket library**, it utilizes TCP/IP protocols to create a server-client architecture for real-time gaming.

---

## 🚀 Features

### 1. **Multiplayer Gameplay**
- Two players can connect over a LAN or ad-hoc wireless network to play Tic-Tac-Toe in real-time.
- Utilizes **TCP/IP protocols** to ensure smooth communication.

### 2. **Server-Client Architecture**
- A dedicated **server** is created to manage game connections.
- Players join a **room** by connecting to the server with a specified IP and port (3000).

### 3. **Localhost and LAN Support**
- Initially runs on **localhost** for testing and debugging purposes.
- Fully functional over a **local area network (LAN)** using tools like **Hamachi**.

### 4. **Reliable and Secure Communication**
- Communication between players is handled through the **socket library**.
- Port **3000** is used for secure and reliable data transmission.

### 5. **Cross-Network Connectivity**
- Players can connect from anywhere over an ad-hoc wireless network using Hamachi.

---

## 🛠️ Technologies Used

- **Python** - Core programming language.
- **Socket Library** - For implementing the TCP/IP server-client architecture.
- **Hamachi** - For creating a virtual LAN network to enable multiplayer gameplay.

---

## 🎮 How to Run the Project

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/FariddBayramov/lan-multiplayer-tictactoe.git
   ```

2. Install the required Python dependencies (if any):
   ```bash
   pip install -r requirements.txt
   ```

3. Run the **server**:
   ```bash
   python server.py
   ```

4. Start the **client** for each player:
   ```bash
   python client.py
   ```

5. Connect to the server using the IP address (via Hamachi or local network):
   - Server IP: `YOUR_LOCAL_IP`
   - Port: `3000`

---


## 🎯 Future Enhancements

- Add a graphical user interface (GUI) for an improved user experience.
- Implement a ranking system for players.
- Enable cross-platform compatibility for broader accessibility.
- Introduce an AI opponent for single-player gameplay.

---

## 🧑‍💻 Author

- **Farid Bayramov** 
- GitHub: [FariddBayramov](https://github.com/FariddBayramov)

---

Thank you for exploring the **LAN Multiplayer Tic-Tac-Toe Game**! 🎮✨ Enjoy seamless gaming with friends over a secure network.

