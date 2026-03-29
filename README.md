# 🚀 Flash Clipboard

> ⚡ Sub-second cross-device clipboard sync for Android ↔ Windows. Built for developers who hate friction.

---

## 🧠 Problem

Developers constantly move small pieces of data between devices:
- code snippets  
- links  
- commands  

Most people use:
- WhatsApp  
- email  
- notes  

👉 This creates unnecessary friction and breaks flow.

---

## ⚡ Solution

Flash Clipboard is a **low-latency clipboard sync system** that works instantly:

- Copy on Android → available on Windows in <1 sec  
- Copy on Windows → available on Android instantly  

No manual steps. No switching apps.

---

## 🔥 Key Features

- ⚡ Real-time sync (<500ms target)
- 🔁 Bi-directional clipboard sync
- 🧠 Clipboard history (last 20 items)
- ⌨️ Quick paste popup (Windows)
- 🔒 Secure device pairing

---

## 🏗️ Tech Stack

- Backend: Node.js + WebSocket  
- Desktop: Python (initial) / Tauri (planned)  
- Android: Kotlin  
- Realtime: Persistent WebSocket connection  

---

## 📦 Architecture

Windows App ⇄ WebSocket Server ⇄ Android App


---

## 🎥 Demo

<!-- Add GIF here before applying -->
<!-- Example: ![Demo](./demo.gif) -->

---

## 🚀 Getting Started

### Backend

cd backend
npm install
node server.js


### Windows Client

cd windows-client
pip install pyperclip websocket-client
python app.py


### Android App
- Install APK (coming soon)

---

## 🧠 Why this exists

This project is part of a larger goal:

> Build a frictionless cross-device workflow system for developers.

---

## 🗺️ Roadmap

- [x] Real-time text sync  
- [x] Android ↔ Windows support  
- [ ] Multi-device sync  
- [ ] File transfer  
- [ ] End-to-end encryption  
- [ ] Dev snippet manager  

---

## 🤝 Contributing

Open to contributions, ideas, and improvements.

---

## 📜 License

MIT
