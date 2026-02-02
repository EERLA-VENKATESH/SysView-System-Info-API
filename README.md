# SysView – System Info API 🚀

SysView is a lightweight **Node.js HTTP API** that exposes real-time system and process information in JSON format. It is designed for learning, monitoring, and quick diagnostics without external dependencies.

---

## 🔧 Features

* 📊 **CPU Information** – model, cores, architecture, load average
* 💾 **Memory Stats** – total, free, and usage percentage
* 👤 **User Info** – system user details
* 🌐 **Network Interfaces** – available network configurations
* ⚙️ **Process Info** – PID, Node.js version, uptime, memory usage
* 🧭 Simple **REST-style endpoints** returning clean JSON

---

## 🛠 Tech Stack

* **Node.js**
* Built-in modules: `http`, `os`, `process`, `url`

(No external libraries used)

---

## 📂 API Endpoints

| Endpoint   | Description                     |
| ---------- | ------------------------------- |
| `/`        | API metadata & available routes |
| `/cpu`     | CPU details                     |
| `/memory`  | Memory usage statistics         |
| `/user`    | Logged-in user info             |
| `/process` | Node.js process details         |
| `/network` | Network interfaces              |

---

## ▶️ How to Run

```bash
node index.js
```

Server will start at:

```
http://localhost:6060
```

---

## 📌 Sample Response (CPU)

```json
{
  "model": "Intel(R) Core(TM) i5",
  "cores": 8,
  "architecture": "x64",
  "loadAVG": [0.42, 0.35, 0.30]
}
```

---

## 🎯 Use Cases

* Learning Node.js core modules
* System diagnostics & monitoring
* Backend interview/demo project
* Foundation for DevOps or monitoring tools

---

## 🚀 Future Enhancements

* Fix route-wise response mapping
* Add authentication
* Add Docker support
* Add frontend dashboard
* Deploy on cloud (Render / Railway)

---

## 👨‍💻 Author

**Eerla Venkatesh**
Backend / Full Stack Developer

---

⭐ If you like this project, don’t forget to star the repo!
