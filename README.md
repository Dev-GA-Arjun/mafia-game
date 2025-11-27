Mafia Multiplayer Game (Frontend)

A simple, clean, and modular **frontend** for a multiplayer Mafia party game.
Players can host a room, join with a PIN, wait in a lobby, and later start the game.
This project uses **pure HTML, CSS, and JavaScript** — no frameworks.

Features

* **Create Room** – Host a lobby and generate a 4-digit PIN
* **Join Room** – Enter a valid PIN and join an existing lobby
* **Waiting Room UI** – Shows a list of connected players
* **Clean Page Flow** – Home → Create Room → Waiting Room → Game
* **Modular Structure** – Each page has its own HTML & CSS
* **Responsive Layout** – Works on mobile and desktop

---

Project Structure

```
/project
│── home.html
│── createRoom.html
│── waitingRoom.html
│── game.html     
│
├── css/
│   ├── home.css
│   ├── createRoom.css
│   ├── waitingRoom.css
│   ├── game.css  
│
|--images/    
│
└── images/
```

---

## 🛠️ Technologies Used

* **HTML5**
* **CSS3** 
* **JavaScript**

---

Purpose of This Project

The goal is to build the full UI of a Mafia game that can later be connected to a backend using:

* FastAPI
* WebSockets (for real-time communication)

This repo currently focuses on **frontend flow and design**.

Current Status

✔ Home page UI
✔ Create room page
✔ Waiting room page
⬜ Game page
⬜ Backend/WebSocket integration


Contributing

Feel free to fork, open issues, or submit pull requests.
Suggestions and improvements are always welcome!
